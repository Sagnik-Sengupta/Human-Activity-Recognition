# Human Activity Recognition

## Overview

This study aimed to compare state-of-the-art image classification models on a custom indoor Human Activity Recognition dataset. The main architectures compared were Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs).

### Dataset

The dataset comprises **25 indoor classes**, organized as follows:

|                      |                      |                      |                      |                      |
|----------------------|----------------------|----------------------|----------------------|----------------------|
| Washing Dishes       | Brushing Teeth       | Cleaning the Floor    | Cooking              | Cutting Veggies      |
| Dancing              | Drinking             | Eating                | Fighting             | Hugging              |
| Laughing             | Phoning              | Pouring a Liquid      | Reading              | Sitting              |
| Sleeping             | Smoking              | Taking Photos         | Texting              | Using a Computer     |
| Watching TV          | Waving Hands         | Writing on a Board    | Writing on a Book    |                      |

You can access the dataset [here](https://www.kaggle.com/datasets/shreyaakuu/har25indoor).

### Models and Accuracies

The models used along with their accuracies are as follows:

| Model            | Accuracy  |
|------------------|-----------|
| ViT              | 84.2%     |
| ResNet50         | 76.1%     |
| MobileNet        | 72.1%     |
| EfficientNetB2   | 62.4%     |
| MobileViT        | 48.2%     |

### Grad-CAM Results

Grad-CAM results are available for the top two performing models, showcasing that **ViT clearly demonstrates a better contextual understanding of complex images**.

---
