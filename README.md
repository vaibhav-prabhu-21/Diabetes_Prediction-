🩺 Diabetes Prediction using Machine Learning with Flask
📌 Project Overview

This project predicts whether a person is diabetic or non-diabetic using Machine Learning techniques based on medical input parameters such as glucose level, BMI, insulin level, blood pressure, and age.

The trained model is deployed using a Flask web application, allowing users to enter health details through a simple interface and receive real-time predictions.

🎯 Objective

To build a Machine Learning classification model that can assist in early detection of diabetes and deploy it using Flask for interactive prediction through a web browser.

📊 Dataset Used

Dataset: PIMA Indians Diabetes Dataset

Features include:

Number of pregnancies
Glucose concentration
Blood pressure
Skin thickness
Insulin level
BMI
Diabetes pedigree function
Age

Target:

0 → Non-Diabetic
1 → Diabetic

⚙️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
TensorFlow / Keras
Flask
HTML, CSS

🧠 Project Workflow
Data preprocessing and missing value handling
Feature selection and scaling using StandardScaler
Train-test split (70% training, 30% testing)
Model training using:
Gaussian Naive Bayes
Random Forest Classifier
Model evaluation using accuracy, confusion matrix, and classification report
Best model saved and deployed using Flask

Random Forest performed better and was selected as the final model.

🌐 Flask Deployment

User workflow:

Enter patient details → Submit form → Model prediction → Result displayed

This makes the project interactive and deployment-ready.

📁 Project Structure
Diabetes-Prediction-ML-Flask-App/
│
├── templates/
├── static/
├── app.py
├── model.keras
├── diabetes_prediction.ipynb
├── requirements.txt
└── README.md
🚀 How to Run the Project

Clone repository

git clone https://github.com/your-username/diabetes-prediction-ml-flask-app.git

Install dependencies

pip install -r requirements.txt

Run Flask app

python app.py

Open browser

http://127.0.0.1:5000/
📈 Model Performance

Random Forest classifier achieved strong prediction accuracy and performed better compared to Gaussian Naive Bayes.

👨‍💻 Author

Vaibhav Prabhu
Machine Learning | Data Science | Deep Learning Enthusiast
