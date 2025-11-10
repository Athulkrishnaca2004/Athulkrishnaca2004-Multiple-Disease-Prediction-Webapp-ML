# Athulkrishnaca2004-Multiple-Disease-Prediction-Webapp-ML

🩺 Multiple Disease Prediction Web App
🚀 Overview

The Multiple Disease Prediction Web App is an AI-powered healthcare application designed to predict various diseases based on user-provided medical parameters. Using machine learning algorithms, the system analyzes data and predicts the likelihood of multiple diseases such as Diabetes, Heart Disease, and Parkinson’s Disease.

The goal of this project is to provide an accessible, accurate, and easy-to-use web interface for early disease detection and preventive healthcare.

🧠 Features

✅ Predicts multiple diseases in a single platform
✅ User-friendly web interface built with Streamlit
✅ Integrates multiple trained Machine Learning models
✅ Fast and accurate predictions based on medical inputs
✅ Secure and lightweight — runs locally or can be deployed on cloud platforms

🏗️ Tech Stack
Component	Technology
Frontend	Streamlit
Backend	Python
Machine Learning	Scikit-learn, NumPy, Pandas
Visualization	Matplotlib, Seaborn
Model Persistence	Pickle (.pkl files)
🩸 Diseases Covered

🩸 Diabetes Prediction — based on glucose level, BMI, blood pressure, and insulin.

❤️ Heart Disease Prediction — based on cholesterol, heart rate, blood pressure, and age.

🧠 Parkinson’s Disease Prediction — based on vocal features and tremor-related attributes.

(You can extend this app to include more diseases such as liver or kidney disorders.)

⚙️ Installation & Setup

Follow these steps to run the project locally:

# 1️⃣ Clone this repository
git clone https://github.com/<your-username>/Multiple-Disease-Prediction-Webapp-ML.git

# 2️⃣ Navigate into the project directory
cd Multiple-Disease-Prediction-Webapp

# 3️⃣ Install the dependencies
pip install -r requirements.txt

# 4️⃣ Run the application
streamlit run app.py


Then open your browser and go to:
👉 http://localhost:8501

📊 Machine Learning Models

Each disease uses a specific ML algorithm for high accuracy:

Disease	Algorithm Used
Diabetes	Support Vector Machine (SVM)
Heart Disease	Logistic Regression
Parkinson’s Disease	Random Forest Classifier

All models are trained and serialized using pickle for easy integration with the web app.

🧬 Dataset Information

Diabetes Dataset: Sourced from Kaggle’s Pima Indians Diabetes Database

Heart Disease Dataset: Cleveland Heart Disease dataset (UCI Repository)

Parkinson’s Dataset: UCI Machine Learning Repository

🌐 Deployment

You can deploy this app easily on:

Streamlit Cloud

Render

Heroku (legacy)

Example:

streamlit run app.py

📚 Future Enhancements

Integration with wearable health monitoring devices

Adding more disease prediction modules (e.g. liver, thyroid, kidney)

Enhanced UI using React or Flask frontend integration

Real-time health tracking and data analytics dashboard
