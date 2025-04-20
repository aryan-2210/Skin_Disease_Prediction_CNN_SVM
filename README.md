# Skin Disease Prediction using CNN & SVM

This project uses a Convolutional Neural Network (CNN) model trained on skin disease images to predict the type of skin condition from an image input. It integrates a simple web interface built with Flask and includes model architecture, training script, and prediction API logic.

---

## 🔍 Problem Statement

Early detection of skin diseases can prevent complications and ensure timely treatment. This project aims to classify nine types of skin conditions based on image data using a deep learning model.

---

## 🧠 Model Overview

- **Architecture**: CNN with two Conv2D layers, MaxPooling, Dropout, and Dense layers
- **Output Layer**: Softmax with 9 disease classes
- **Training**: Done using Keras' `ImageDataGenerator`
- **Classification**: The model outputs probabilities for each class, sorted in descending order

> Example Predicted Class: `Basal cell carcinoma`

---

## 📁 Project Structure

