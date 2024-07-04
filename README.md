# DLP_CIFAR-10-Object-Recognition-using-ResNet50
**Overview**

This repository contains a deep learning model for object recognition on the CIFAR-10 dataset using ResNet50 as the base architecture. The model achieves improved accuracy through scaling and fine-tuning.

**Dataset**

- CIFAR-10: a popular dataset for object recognition tasks, consisting of 60,000 32x32 color images in 10 classes (6,000 images per class).
- this dataset was imported through kaggle using API

**Model**

- ResNet50: a deep residual network architecture with 50 layers, pre-trained on ImageNet.
- Scaling: input images were scaled to improve model performance.
- Fine-tuning: the pre-trained ResNet50 model was fine-tuned on the CIFAR-10 dataset to adapt to the new task.

**Performance**

- Accuracy-before: 71.65%
-  Accuracy-before: 82.85%

Usage

1. Install required dependencies: TensorFlow, Keras,cv2,os,py7zr,PIL.
2. Download the CIFAR-10 dataset and preprocess images according to the scaling method used.
3. Load the pre-trained ResNet50 model and fine-tune it on your dataset.
4. Evaluate the model using the provided code.
