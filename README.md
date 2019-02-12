# Flower Recognition
Image Classification using a CNN on Flowers🌷

In this notebook, we will train a CNN-based image classifier to classify a couple thousand images of flowers, loaded from a directory on google drive.

We will compare three pretrained model: **VGG16, ResNet50, Inception**

The training will take **data augmentation, fine-tune**

### Accuray comparasion:
* Convnet without data augmentation: 63%
* Convnet with data augmentation: 70%
* VGG: 80% **(Winner)**
* ResNet50: 67%
* InceptionV3: 75%

### conclusion
* **VGG16** converges quicker than **ResNet50**
* The training data and validation data of **VGG16** improves steadly, while **ResNet50** is hard to improve validation accuracy at first, but imporves quickly after a certain epoch
* The **InceptionV3** has very low loss but it's validation accuary still not improve
