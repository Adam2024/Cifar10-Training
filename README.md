# Train CIFAR10 with PyTorc
I'm playing with PyTorch on the CIFAR10 dataset.And I will try ResNet18 and VGG16 models respectively.

## Prerequisites
- Python 3.7+
- PyTorch 1.2+

## Experimental background
This experiment is the first experiment of artificial intelligence security, using pytorch to solve the classification problem of the cifar10 data set.

## Experiment procedure
In this process, I first tried to use ResNet18, but the correct rate was always around 80%. Later, I tried VGG16 and it was still the same. Finally, I checked the training and test loss graphs to find the problem. The training epoch was too small, so I adjusted the epoch to 200, which is accurate. The rate can reach 93%.

## Start the train 
python train.py 

## Accuracy
| Model             | Acc.        |
| ----------------- | ----------- |
| [VGG16](https://arxiv.org/abs/1409.1556)              | 92.64%      |
| [ResNet18](https://arxiv.org/abs/1512.03385)          | 93.02%      |
