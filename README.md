# Brain_tumour_classifer
Brain Tumor Classification using Deep Learning
Project Overview

This project implements a deep learning–based image classification system to detect and classify brain tumors from MRI scan images. The solution uses Convolutional Neural Networks (CNNs) to automate medical image analysis and support early diagnosis.

Features

Automated brain tumor detection from MRI images

Multi-class image classification

Image preprocessing and visualization

Trained model can be reused without retraining

Tech Stack

Programming Language: Python

Libraries and Frameworks: TensorFlow, Keras, NumPy, Matplotlib, OpenCV

Platform: Google Colab

Model Type: Convolutional Neural Network (CNN)

Dataset

MRI brain scan images categorized into multiple tumor classes

Includes both tumor and non-tumor images

Images are resized and normalized before training

Note: The dataset can be replaced or extended for further experimentation.

Methodology

Data Loading and Preprocessing

Image resizing and normalization

Train-test split

Model Architecture

Convolution and MaxPooling layers

Fully connected Dense layers for classification

Training

Optimizer: Adam

Loss Function: Categorical Cross-Entropy

Evaluation

Accuracy and loss visualization

Testing on unseen MRI images

Model Saving

Trained model saved for future inference

Results

Achieved strong performance on validation data

Model effectively classifies MRI images into respective tumor categories

Training and validation performance visualized using plots

How to Run

Clone the repository

git clone https://github.com/your-username/brain-tumor-classifier.git


Open the notebook in Google Colab or Jupyter Notebook

Install required dependencies

Run all cells sequentially

Model Persistence

The trained model is saved and can be loaded later to perform predictions without retraining.

Future Enhancements

Deployment as a web application

Performance improvement using transfer learning

Addition of more tumor classes

Integration of explainable AI techniques

Author

Tejaswi Yadav

GitHub: https://github.com/your-username

LinkedIn: https://linkedin.com/in/your-profile

License

This project is licensed under the MIT License.

