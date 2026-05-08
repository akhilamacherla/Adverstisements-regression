# 📈 Advertising Sales Prediction

A simple Machine Learning web application built using Streamlit that predicts product sales based on advertising budgets spent on:

TV Advertising
Radio Advertising
Newspaper Advertising

The project uses Linear Regression from Scikit-learn and provides an interactive UI for prediction.

# 🚀 Features
Interactive Streamlit Web App
Predicts sales instantly
Uses Machine Learning Linear Regression model
Standardized input features using StandardScaler
Simple and beginner-friendly project
# 🛠️ Technologies Used
Python
Streamlit
NumPy
Pandas
Scikit-learn
Pickle
📂 Project Structure
├── app.py                  # Streamlit web application
├── train.py                # Model training script
├── requirements.txt        # Required libraries
├── advertising_model.pkl   # Saved trained model
├── Advertising.csv         # Dataset
└── README.md               # Project documentation
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/advertising-sales-prediction.git
cd advertising-sales-prediction

Install dependencies:

pip install -r requirements.txt
▶️ Train the Model

Run the training script:

python train.py

This will:

Train the Linear Regression model
Scale the features
Save the model as advertising_model.pkl
# 🌐 Run the Streamlit App

Start the application:

streamlit run app.py
# 📊 Input Features

The app takes the following advertising budgets as input:

Feature	Description
TV	Budget spent on TV ads
Radio	Budget spent on Radio ads
Newspaper	Budget spent on Newspaper ads
# 📈 Model Used

The project uses:

LinearRegression()

from Scikit-learn.
