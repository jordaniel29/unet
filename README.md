# UNet Segmentation

UNet for segmentation problem 

## Environment
- Windows
- Python 3.9
- PyTorch 2.2.1

## Installation
1. Install PyTorch from this link https://pytorch.org/get-started/locally/ <br />
Note: if there are problems when running the PyTorch please reinstall it using this command (only for CUDA)
```bash
pip install torch==2.2.1+cu118 torchvision==0.17.1+cu118 --index-url https://download.pytorch.org/whl/cu118
```
2. Install the required dependencies 
```bash
pip install -r requirements.txt
```

## Data
The dataset used is Carvana dataset. You can download the training dataset through one of these links 
- https://www.kaggle.com/c/carvana-image-masking-challenge/data
- https://drive.google.com/drive/folders/18YxLRaWTjxxhQ19BGKf0pgAbEj_1jv3b?usp=sharing 

## How to Run
1. Make sure that you have downloaded the data
2. Run the training using this command
```bash
python train.py
```
