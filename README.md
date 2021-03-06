# MSDS19069_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# Part 1

Dataset: https://drive.google.com/open?id=1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR

Models: https://github.com/Hamzha/MSDS19069_COVID19_DLSpring2020/blob/master/weights/Weights%20Links.txt

## Accuracy and Confusion Matrix

### Accuracy for VGG-16 with custom layers at the end is 59%

#### valid
![](graphs/VGG-16%20first%20valid.png)

#### test
![](graphs/VGG-16%20first%20test.png)

### Accuracy for ResNet-18 with custom layers at the end is 58%

#### valid
![](graphs/ResNet-18%20first%20valid.png)

#### test
![](graphs/ResNet-18%20first%20test.png)

### Accuracy fow VGG-16 with few Convolution layers freeze is 59%

#### valid
![](graphs/VGG-16%20few%20layers%20valid.png)

#### test
![](graphs/VGG-16%20few%20layers%20test.png)

### Accuracy fow ResNet-18 with few Convolution layers freeze is 52%

#### valid
![](graphs/ResNet-18%20few%20valid.png)
#### test
![](graphs/ResNet-18%20few%20test.png)

### Accuracy fow VGG-16 accuracy is 59%

#### valid
![](graphs/VGG-16%20full%20valid.png)
#### test
![](graphs/VGG-16%20full%20test.png)

### Accuracy for ResNet-18 accuracy is 46%

#### valid
![](graphs/ResNet-18%20full%20valid.png)
#### test
![](graphs/ResNet-18%20full%20test.png)

## Part 2

Models: https://drive.google.com/open?id=1OqMepcZ-vVqftYiM-_x3glDTCmr6I7V7

Dataset: https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view?usp=sharing

### VGG without Focal Loss

![](graphs/VGG%20Simple%20Matrices.PNG)

### VGG with Focal Loss

![](graphs/VGG%20Focal%20Loss%20Matrices.PNG)

### ResNet without Focal Loss

![](graphs/ResNet%20Simple%20Matrices.PNG)

### ResNet with Focal Loss

![](graphs/ResNet%20Focal%20Loss%20Matrices.PNG)
