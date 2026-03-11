# Flower Classification Web App using CNN and Flask

This project is an end-to-end deep learning application that classifies flower images using a Convolutional Neural Network (CNN) with MobileNetV2 and provides predictions through a Flask-based web interface.

The system allows users to upload an image, predicts the flower category, and displays a short description of the predicted flower.

##  Project Overview

The goal of this project is to build a complete machine learning application including model training, prediction, and UI deployment.

The model is trained using transfer learning with MobileNetV2 and integrated with a Flask web application for real-time prediction.

##  Features

- Image classification using CNN
- Transfer learning with MobileNetV2
- Flask-based web UI
- Image upload for prediction
- Flower name prediction
- Auto-generated flower description
- Real-time inference
- Model integration with backend

##  Technologies Used

- Python
- TensorFlow / Keras
- CNN (Convolutional Neural Network)
- MobileNetV2
- Flask
- HTML / CSS (for UI)
- NumPy
- Matplotlib

##  Project Files

- app.py → Flask application
- model.h5 → Trained CNN model
- Final_MajorFile.ipynb → Training notebook
- static/ → CSS / images
- README.md

##  Workflow

1. Train CNN model using flower dataset
2. Save trained model
3. Build Flask backend
4. Create UI for image upload
5. Load model in Flask app
6. Predict flower class
7. Show prediction with description

##  How it works

1. User uploads image from UI
2. Flask sends image to model
3. Model predicts flower type
4. App shows flower name + description

##  Output

- Predicted flower name
- Description of flower
- Real-time result in UI

##  Author

Archie Patel  
B.Tech CSE (Data Science)  
Machine Learning | Deep Learning | NLP | Flask | Python
