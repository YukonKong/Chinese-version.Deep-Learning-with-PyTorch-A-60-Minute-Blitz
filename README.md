# 英文原文：Deep Learning with PyTorch: A 60 Minute Blitz
### 作者： Soumith Chintala
原文地址：https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html

=====================

## What is PyTorch?
什么是 PyTorch？

### PyTorch is a Python-based scientific computing package serving two broad purposes:
PyTorch 是一个基于 Python 的科学计算软件包，服务于两个广泛的目的：

### 1.A replacement for NumPy to use the power of GPUs and other accelerators.
1.一个利用 GPU 和其他加速器能力的 NumPy 替代品。
### 2.An automatic differentiation library that is useful to implement neural networks.
2.一个用于实现神经网络的自动微分库。



## Goal of this tutorial: 
本教程的目标：
### 1.Understand PyTorch’s Tensor library and neural networks at a high level.
1.理解 PyTorch 的 Tensor 库和神经网络的高级概念。
### 2.Train a small neural network to classify images
2.训练一个小型神经网络以进行图像分类

### To run the tutorials below, make sure you have the torch, torchvision, and matplotlib packages installed.
为确保正常运行以下教程，请确保已安装 torch、torchvision 和 matplotlib 包。

=====================

翻译方式：GLM-4大模型 + 手动调整

翻译规则：
- 标题：英文原文之后紧跟 括号包裹的中文译文
- 内容：英文原文的下一行 即对应中文译文
- 代码注释：中文译文替换英文原文

