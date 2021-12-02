## Overview


## Datasets


## Requirements and install
1. Create virtual environment
Create virtual environment with python version 3.7. Then Activate your virtual environment
```bash
conda create –n test python=3.7
conda activate test
```

2. Install requirements
```bash
pip install -r requirements.txt
```
 or
```bash
pip install numpy
pip install pillow
pip install scikit-learn
pip install tqdm
pip install matplotlib
pip install visdom
pip install timm
pip install opencv   or   conda install -c conda-forge opencv
```

3. Download Pre-train model

 Download Deeplab V3+ Pre-train model from [Deeplab V3+](https://github.com/VainF/DeepLabV3Plus-Pytorch) and put it in DeepLabV3/checkpoints folder

 Download MiDaS Pre-train model from [MiDaS](https://github.com/isl-org/MiDaS) and put it in MiDaS/weights folder

 Download Co-Modulated-GAN Pre-trian model using the command below and put it in checkpoints folder
```bash
download places512.sh
```
or
```bash
download ffhq512.sh
```

## RUN
1. test.py



2. test_ffhq 부분 사용법 설명 + 이미지



3. test_one_image.ipynb 사용법 설명 + 이미지


