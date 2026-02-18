🌊 Flood Prediction using Machine Learning
📌 Project Overview

This project aims to predict the probability of flood occurrence using Machine Learning techniques based on environmental and geographical features. A user-friendly web interface is developed using Flask where users can enter input parameters and receive flood prediction results instantly.
The system helps in early warning and decision-making by analyzing factors like rainfall, population density, drainage, and geographical data.

🎯 Objective
Build a machine learning model to predict flood probability.
Handle data imbalance using SMOTE.
Deploy the trained model using Flask.
Create an easy-to-use web interface for predictions.

🗂️ Dataset
The dataset contains environmental and geographical factors related to flood occurrence.
Example Features:
Latitude
Longitude
Elevation
Distance from river
Population density
Built-up area
7-day rainfall
Monthly rainfall
Drainage level
(Target) Flood Probability

⚙️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
SMOTE (Imbalanced-learn)
Flask
HTML/CSS

🔄 Project Workflow
 1 Data Collection
 2 Data Preprocessing
 3 Handling missing values
 4 Feature scaling

Train-test split
3️⃣ Handling Imbalanced Data using SMOTE
4️⃣ Model Training (Random Forest Classifier)
5️⃣ Model Evaluation
6️⃣ Model Saving (pickle/joblib)
7️⃣ Flask Web Application Development
8️⃣ Frontend Integration
9️⃣ Real-time Prediction

🤖 Machine Learning Model

Random Forest Classifier is used because:
High accuracy
Handles non-linear relationships
Reduces overfitting using multiple decision trees

📊 Evaluation Metrics

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC-AUC Score

🌐 Web Application

Users enter required environmental values in the web form, and the system predicts flood probability instantly.

Features:

Simple UI

Real-time prediction

Input validation

Easy deployment

📂 Project Structure
Flood_Prediction_Project/
│
├── app.py                 # Flask backend
├── model.pkl              # Trained ML model
├── templates/
│     └── index.html       # Frontend page
├── static/
│     └── style.css
├── preprocessing.py
├── training.py
└── README.md

▶️ How to Run the Project
Install required libraries:
pip install -r requirements.txt
Run Flask app:
python app.py

Open browser:

http://127.0.0.1:5000/
