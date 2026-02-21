# Face Emotion AI

![Python](https://img.shields.io/badge/python-3.10-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Issues](https://img.shields.io/github/issues/<username>/<repo_name>) ![Kaggle Dataset](https://img.shields.io/badge/dataset-FER--2013-orange) ![Hugging Face]([https://img.shields.io/badge/deploy-HuggingFace-purple](https://huggingface.co/spaces/rohit-profile/Face-Emotion-AI))

## Project Overview
Face Emotion AI is a computer vision project that detects human emotions from facial expressions. Using deep learning, this project classifies emotions such as happiness, sadness, anger, surprise, fear, disgust, and neutral. The model can be deployed in applications like mood tracking, mental health monitoring, and human-computer interaction systems.  

The project uses **Flask** for the backend and HTML/CSS for the frontend, and it is deployed on **Hugging Face Spaces**.

---

## Live Deployment

You can explore the live demo of Face Emotion AI here:
🔗 [View on Hugging Face Spaces](https://huggingface.co/spaces/rohit-profile/Face-Emotion-AI)

---
## Dataset
This project uses the **FER-2013 (Facial Expression Recognition) dataset** from Kaggle.  
The dataset contains grayscale images of faces labeled with seven emotion categories.  

**Download the dataset:** [FER-2013 Kaggle Dataset](https://www.kaggle.com/datasets/msambare/fer2013)

| Column / Feature | Description |
|-----------------|-------------|
| `pixels`        | Flattened 48x48 grayscale image pixel values |
| `emotion`       | Emotion label (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral) |
| `Usage`         | Whether the image is for training, public test, or private test |

---

## Project Objectives
1. **Data Preprocessing** – Convert pixels to images, normalize, and split into train/test sets.  
2. **Model Development** – Build CNN (Convolutional Neural Network) for emotion classification.  
3. **Model Evaluation** – Use metrics like Accuracy, F1-score, Confusion Matrix.  
4. **Deployment** – Create a web app for live emotion detection using Flask and HTML, deployed on Hugging Face Spaces.

---

## Methodology
1. **Data Cleaning & Preprocessing** – Normalize pixel values, reshape images, one-hot encode labels.  
2. **Exploratory Data Analysis (EDA)** – Visualize sample images per emotion category.  
3. **CNN Model Building** – Sequential convolutional layers with pooling, dropout, and dense layers.  
4. **Model Training** – Use training set with validation split, optimize with Adam optimizer.  
5. **Evaluation & Interpretation** – Confusion matrix, accuracy curves, and class-wise performance.  
6. **Deployment** – Real-time emotion detection via Flask web app with HTML frontend.

---

## Tools & Libraries
- **Python**  
- **TensorFlow / Keras**  
- **Flask**  
- **OpenCV**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **HTML / CSS / JavaScript**  

---
## Live Link-->(https://huggingface.co/spaces/rohit-profile/Face-Emotion-AI)
---

