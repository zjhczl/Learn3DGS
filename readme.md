# 3DGS
## 环境配置
### 安装vs_community__2019
勾选c++桌面工具安装
### 安装cuda11.8
https://developer.nvidia.com/cuda-toolkit-archive
### 加入环境变量Path
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.8
### 使用conda创建环境
```
conda create -n gaussian_splatting python=3.10
conda activate gaussian_splatting
pip install torch==2.0.0+cu118 torchvision==0.15.0+cu118 torchaudio==2.0.0+cu118 --index-url https://download.pytorch.org/whl/cu118
pip install plyfile tqdm opencv-python joblib
```