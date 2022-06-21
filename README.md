# Nerve detection in Brachial Plexus Ultrasound Videos

## Installation

Create conda environment and activate it

```b
conda create --name crossvis python=3.8
conda activate crossvis
```
Load cuda 10.2 and cudnn/7.6.5-cuda-10.2
```b
module load u18/cuda/10.2
module load u18/cudnn/7.6.5-cuda-10.2
```
Install torch and torchvision
```b
pip install torch==1.10.0+cu102 torchvision==0.11.0+cu102 torchaudio==0.10.0 -f https://download.pytorch.org/whl/torch_stable.html
```
