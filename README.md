# Efficient Convolutional Neural Networks on Raspberry Pi for Image Classification

cifar10triplenet/main.py is the main file that we also worked on.
cifar10triplenet/models/TripleNet_S.py is the main file we worked on.
all .pth files are outputs from the various models we ran, they are only important when running the pretrain moniker. 

## Abstract
TripleNet is adopted from the concept of block connections in ThreshNet, it compresses and accelerates the network model, reduces the amount of parameters of the network, and shortens the inference time of each image while ensuring the accuracy. TripleNet and other state-of-the-art (SOTA) neural networks perform image classification experiments with the CIFAR-10 and SVHN datasets on Raspberry Pi. The experimental results show that, compared with MobileNet, ThreshNet, EfficientNet, and HarDNet, the inference time of TripleNet per image is shortened by 16%, 17%, 24%, and 30%, respectively.

