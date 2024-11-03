
# Potato Disease Classifier

## Project Overview

This project aims to classify images of potato plants into different categories based on their health status. Using a Convolutional Neural Network (CNN), the model predicts whether a potato plant is affected by early blight, late blight, or is healthy. The project utilizes TensorFlow and Keras for building and training the model.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Training the Model](#training-the-model)
- [Results](#results)

## Installation

To run this project, you need to install the necessary Python packages. You can do this using pip. Here are the required libraries:

- numpy
- matplotlib
- opencv-python
- tensorflow

You can install these packages by running the following command:

```bash
pip install numpy matplotlib opencv-python tensorflow
```

## Clone the Repository

After installing the required packages, clone this repository to your local machine using:

```bash
git clone https://github.com/gaurank11/PlantDiseaseClassifier
```

## Dataset

Download Dataset - https://www.kaggle.com/datasets/emmarex/plantdisease 

The dataset used for this project is the PlantVillage dataset, which contains images of potato plants categorized as healthy, early blight, or late blight. Ensure that you have the dataset organized as follows:

```
PlantVillage/
├── Potato___Early_blight/
├── Potato___Late_blight/
└── Potato___healthy/
```

## Usage

To run the classification model, ensure you have the dataset in the correct directory structure. You can then run the main script that includes data preprocessing, model building, training, and evaluation.

## Model Architecture

The model architecture consists of a Convolutional Neural Network (CNN) with the following layers:

- Convolutional layers for feature extraction.
- Max pooling layers for down-sampling.
- Dense layers for classification using Softmax activation.

## Training the Model

To train the model, execute the main script. The model will be trained on the training dataset and validated using a portion of the dataset. The training process can be monitored through the console output.

![image](https://github.com/user-attachments/assets/2ba90696-46a3-4901-a012-6e21f9d9a850)


## Results

After training, the model can predict the health status of potato plants based on new images. Evaluate the model's performance using the validation accuracy and loss metrics printed during training.

