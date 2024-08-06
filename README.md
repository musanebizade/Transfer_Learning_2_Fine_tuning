# Transfer Learning and Fine-Tuning for Image Classification 📷
In this project I used 10_food_classes data. The dataset is organized into 2 folders (train, test) and contains subfolders for each car category. There are 10.000 images (JPG) and 10 classes(chicken_curry, chicken_wings, fried_rice, grilled_salmon, hamburger, ice_cream, pizza, ramen, steak, sushi) in this data. I used EfficientNetV2B0 model in this task and took 1, 10 and finally all data for training process.The focus is on using pre-trained models to enhance the performance of image classification tasks.
## Project Overview

The notebook demonstrates the process of fine-tuning pre-trained models using different amounts of data. Specifically, it covers:

- Fine-tuning with 10% of the data
- Fine-tuning with all available data

## Key Steps

1. **Model 3: Fine-Tuning with 10% Data**
    - This section details the process of fine-tuning a pre-trained model using only 10% of the dataset.
    - The objective is to evaluate how well the model can perform with a limited amount of data.
2. **Model 4: Fine-Tuning with All Data**
    - Here, the model is fine-tuned using the entire dataset.
    - The goal is to achieve the highest possible accuracy by utilizing all available data for training.

## Key Components

- **Transfer Learning:** Utilizing pre-trained models such as VGG16, ResNet50, or InceptionV3.
- **Fine-Tuning:** Refining the weights of the pre-trained network to better suit the specific image classification task.
- **Data Management:** Efficient handling and preprocessing of data to ensure optimal training performance.
