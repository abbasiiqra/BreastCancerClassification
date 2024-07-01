Breast Cancer Classification Website Using Neural Network
Overview:
This project involves the development of a web application that classifies breast cancer types using a neural network. The website allows users to input medical data and receive a prediction about whether the breast cancer is benign or malignant. This project leverages a neural network model trained on the Breast Cancer Wisconsin dataset.

Features:
User-Friendly Interface: A simple and intuitive web interface for inputting medical data.
Neural Network Prediction: Utilizes a trained neural network model to classify the breast cancer type.
Real-Time Results: Instantaneous prediction results upon data submission.
Data Visualization: Visualization of input features and prediction results for better understanding.
Getting Started:

1.Prerequisites
Python 3.7.3
Flask
TensorFlow/Keras
Scikit-learn
Pandas
NumPy

Installation:

Clone the Repository:
git clone https://github.com/abbasiiqra/BreastCancerClassification.git
cd BreastCancerClassification

Create a Virtual Environment:
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

Install Dependencies:
pip install -r requirements.txt

Run the Application:
flask run

Access the Website:
Open your web browser and go to http://127.0.0.1:5000/.

Directory Structure:
breast-cancer-classification/
|--.venv
|── static/
|  |--images
|── templates/
|  |--index.html
├── app.py
└── model.pkl
├── data/
│  ├── data.csv
├── models/
│  ├── Breast_Cancer_Calssification_with_NN_Iqra.ipynb
├── README.md
├── requirements.txt
└── .gitignore
Usage
Navigate to the Website:
Enter http://127.0.0.1:5000/ in your web browser to access the web application.

Input Medical Data:
Fill in the required medical features (such as radius, texture, perimeter, area, smoothness, etc.).

Get Prediction:
Click the "Predict" button to receive the classification result (benign or malignant).


