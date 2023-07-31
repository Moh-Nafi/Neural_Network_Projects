# Building an Image Classification Model using CNN
![cats_vs_dogs_samples](https://github.com/Moh-Nafi/Neural_Network_Projects/assets/133475571/ece10b6b-0f95-4424-8cb4-c5e129de8aec)


Encountering situations where we need to train an image classification model with limited data is quite common, especially in professional computer vision applications.

The term "few" samples can encompass a range, spanning from a few hundred to a few tens of thousands of images. To illustrate, we will focus on a specific scenario: classifying images as "dogs" or "cats" using a dataset containing 4000 pictures, equally split between cats and dogs (2000 each). Our approach involves using 2000 images for training, 1000 for validation, and the remaining 1000 for testing.

In this project, we will explore a fundamental strategy to address this challenge: training a new model from scratch with our limited data. Initially, we will train a small ConvNet on the 2000 training samples without applying any regularization, serving as our baseline to assess achievable performance. The primary concern here will be overfitting. Subsequently, we will introduce the concept of data augmentation, a powerful technique to combat overfitting in computer vision. Leveraging **data augmentation** will enable us to enhance our network's performance, achieving an accuracy of 82%.
