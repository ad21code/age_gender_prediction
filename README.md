# age_gender_prediction
Age and Gender Prediction App using CNN
A deep learning project that predicts a person’s age and gender from an image using a Convolutional Neural Network (CNN). The model is trained on facial images and deployed as an interactive web application.
Overview
This project uses Convolutional Neural Networks (CNNs) to classify human faces into:
Gender: Male / Female
Age Group: Typically classified into age ranges (e.g., 0–2, 4–6, 8–13, 15–20, etc.)
The app processes input images, detects the face region, resizes it to a fixed shape, and passes it to the trained CNN model for prediction.
✨ Features
✅ Predicts age and gender from any human face image ✅ Built with TensorFlow / Keras CNN ✅ Supports both training and deployment modes ✅ Easily exportable model (.h5 format) ✅ Optional Flask / Streamlit web interface for live demos
🧰 Tech Stack
Language: Python
Deep Learning Framework: TensorFlow / Keras
Libraries: NumPy, OpenCV, Matplotlib, Scikit-learn
Deployment (optional): Flask / Streamlit
IDE: Jupyter Notebook / VS Code
📊 Dataset
Commonly used datasets for training include:
UTKFace Dataset
Adience Benchmark Dataset
Each image file typically encodes the age and gender in its filename (e.g., 25_0_0_20170116174525125.jpg → 25 years old, Male).


