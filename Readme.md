<p align="center">
  <img src="Logo GymThings.png" height="150" />
</p>
<h2 align="center">GymThings: Snap and Figure It Out! Project </h2>

# GymThings: Snap and Figure It Out! 
Beginners often struggle with using gym equipment, hindering their fitness journey. Many people lack the necessary knowledge and experience to use gym equipment effectively, resulting in injuries and inefficient workouts.

GymThings application that can detect and identify the function of gym equipment by taking pictures of the gym equipment that users want to use through a smartphone camera. After that, information about the equipment and how to use it will appear. This application can help users to understand what equipment they use and how to use it, so it can help people who are just starting to exercise.

In other words, GymThings is application that can help beginners how to face using gym equipment by only scan the gym equipment than the name of the equipment and how to use it will appear itself.

## Feature
- Scan the gym equipment
- Show the name of the equipment
- Tell users how to use the equipment


## Tech
- [Google Colab](https://colab.research.google.com/drive/1iaRufRwf0EWYWkNPRQVd2bpbg9QKGgw-) - Notebook
- [GitHub](https://github.com/Capstone-Bangkit/ml/tree/main/data) - Dataset

## Dataset
The dataset used for training and evaluation consists of labeled images of gym equipment. The dataset is divided into six classes, each representing a specific type of gym equipment. The classes are as follows:
1. Bench press
2. Bicycle
3. Leg press
4. Pec deck
5. Rowing
6. Treadmill

The dataset is split into training and validation sets. The training set is used to train the model, the validation set is used for hyperparameter tuning.

## Model
The image classification model is developed using deep learning techniques. Convolutional Neural Networks (CNNs) are employed to extract relevant features from the input images. The model is trained using the training set and optimized using a suitable loss function and an appropriate optimizer. The hyperparameters are tuned using the validation set to achieve optimal performance.

## Output
The output of capstone.ipynb notebook is a TFLite model with name __model.tflite__

## Installation
- Clone this repository
  ```bash
  git clone https://github.com/Capstone-Bangkit/ml.git
  ```

## C23-PC683 Capstone Project
1. Difa Putri Chairunisa – Telkom University (A360DSY3548)
2. Rafid Munawir – Sepuluh Nopember Institute of Technology (M038DKX4800)
3. Alfina Rahmawati – Diponegoro University (M166DSY3314)
4. Rizqulloh Rayhan Ferdiansyah – Sebelas Maret University (M340DSX3721)
5. Anggoro Yudha Pratama – Esa Unggul University (C168DSX2681)
6. Muhammad Akmal – Bina Insani University (C148DSX0675)
