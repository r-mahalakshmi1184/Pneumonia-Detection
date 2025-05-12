# Pneumonia Detection Using Deep Learning 
This mini project aims to detect Pneumonia in chest X-ray images using a Convolutional Neural Network (CNN)-based deep learning approach. The model is built using TensorFlow/Keras and visualized with Matplotlib and Seaborn.

# Dataset
The project uses the Chest X-ray Images (Pneumonia) dataset from Kaggle. It includes:
Train and Test folders
NORMAL class: Healthy chest X-rays
PNEUMONIA class: Infected chest X-rays

# The dataset is structured as:
css
Copy
Edit
chest_xray/
│
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
├── test/
│   ├── NORMAL/
│   └── PNEUMONIA/
# Tech Stack
Python
TensorFlow & Keras
OpenCV
Seaborn, Matplotlib
Pandas, NumPy
Google Colab (for training)

# Project Highlights
Image data preprocessing using ImageDataGenerator
Dataset visualization using Seaborn
CNN architecture design using Keras
Train/Test split & label handling with pandas
Random seed control for reproducibility

# Data Visualization
The dataset class distribution is visualized using Seaborn count plots to understand class imbalance and sample size:
python
Copy
Edit
ax = sns.countplot(x='class', data=df_train, palette="mako")
# Folder Structure
bash
Copy
Edit
.
├── Pneumonia_Detection.ipynb
├── README.md
└── chest_xray/
    ├── train/
    ├── test/
# Requirements
Install the necessary libraries using:
bash
Copy
Edit
pip install tensorflow opencv-python matplotlib seaborn pandas
Or use Google Colab, where most libraries are pre-installed.
