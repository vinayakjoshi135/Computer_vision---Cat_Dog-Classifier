
# Cats vs Dogs Image Classifier

A Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify images of cats and dogs.

## Features
- Image preprocessing and augmentation using `ImageDataGenerator`
- CNN architecture with Conv2D, MaxPooling, Dropout, and Dense layers
- Binary classification (Cat vs Dog)
- Model training with validation monitoring
- Accuracy visualization
- Saved trained model (`cat_dog_model.h5`)

## Dataset
Dataset used: Dogs vs Cats from Kaggle

https://www.kaggle.com/datasets/salader/dogsvscats

Expected structure:

archive/
├── train/
│   ├── cats/
│   └── dogs/
└── test/
    ├── cats/
    └── dogs/

## Installation

```bash
git clone <your-repository-url>
cd <repository-name>
pip install -r requirements.txt
```

## Run the Notebook

```bash
jupyter notebook classifier.ipynb
```

## Model Architecture
1. Conv2D + MaxPooling
2. Conv2D + MaxPooling
3. Conv2D + MaxPooling
4. Flatten
5. Dense Layers
6. Dropout
7. Sigmoid Output Layer

## Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Metric: Accuracy
- Image Size: 128x128
- Batch Size: 32

## Output
- Trained model: `cat_dog_model.h5`
- Accuracy and validation accuracy graphs

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Author
Vinayak Joshi
