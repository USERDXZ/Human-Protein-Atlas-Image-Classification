# Human Protein Atlas Image Classification

Kaggle——人类蛋白质图像分类

A榜：141/2172 B榜：179/2172 铜牌

[赛题地址](https://www.kaggle.com/c/human-protein-atlas-image-classification)

### 环境

- ubuntu18.04/windows10
- python 3.6.2
- torch 0.4.1 torchvision 0.2.1
- opencv-python 3.4
- fastai 0.7.0

### 文件说明

- example.ipynb——框架fastai，baseline
- HPA-RES18-KF.ipynb——框架fastai，模型ResNet18，conv_1 4通道，使用k-flods
- HPA-RES34-RGB.ipynb——框架fastai，模型ResNet34，三通道
- moredata.py——HPA外部数据下载
- newConvLearner.py——生成conv_1 4通道预训练模型

### Model

1.ResNet18，34，50

### 总结

fastai功能很强大，例如TTA

K-flods 模型集成在这个比赛中很重要，提升很明显

稀有类型基本在公榜，并且有泄露