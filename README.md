# Vision-transformer-Pruning-in-case-of-Cifar-10


This is an unofficial and elementary implementation of An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.


I use pytorch for implementation.


Usage
python train_cifar10.py # vit-patchsize-4


python train_cifar10.py --patch 2 # vit-patchsize-2


python train_cifar10.py --net res18 # resnet18

Results:

Accuracy

ViT patch=2	 - > 80%

ViT patch=4	 - >80%

ViT patch=8	 - > 30%


Pruning

python vitprune.py

Then I used the saved model to finetune.

Reference


Visual Transformer Pruning

https://arxiv.org/abs/2104.08500
