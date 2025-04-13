# 🌾 Crop Recommendation System

This is a machine learning–based crop recommendation system that predicts the most suitable crop to grow based on environmental and soil conditions. The system integrates a trained ML model with a React-based frontend and a Flask API backend.

## 🎯 Project Objective

To support sustainable agriculture by helping farmers make data-driven decisions about crop selection using soil nutrient levels and weather patterns.


## 🧠 How It Works

Users provide the following inputs:
- **N**itrogen, **P**hosphorus, **K** (Potassium)
- **Temperature** (°C)
- **Humidity** (%)
- **Soil pH**
- **Rainfall** (mm)

The system processes this input through a trained machine learning model and returns the **best crop recommendation** for cultivation under those conditions.


## 💼 My Role: 

As part of this group project, I took the lead on the data science and machine learning components, contributing to the system’s predictive capabilities. Specifically:

- 📊 **Data Cleaning & Preprocessing**: Handled missing values, normalized features, and prepared the dataset for training.
- 📈 **Exploratory Data Analysis**: Used Seaborn & Matplotlib to visualize relationships between soil/weather variables and crop output.
- 🧪 **Model Development & Evaluation**:
  - Trained multiple classifiers (e.g., Random Forest, Decision Tree, SVM).
  - Evaluated them using accuracy, precision, recall, and F1-score.
  - Tuned hyperparameters for optimal performance.
- 💾 **Model Deployment**:
  - Saved the final model using `joblib`.
  - Deployed it via a REST API built in Flask.
- 🔁 **Frontend Integration**: Worked with the team to link the ML backend to a React UI for real-time crop predictions.

> This project strengthened my skills in **machine learning, model deployment, Flask APIs, and full-stack integration** — all of which are highly relevant for data science internships.


## 🛠️ Tech Stack

- **Frontend**: React.js, CSS
- **Backend**: Python, Flask
- **ML Tools**: Pandas, Scikit-learn, Seaborn, Matplotlib
- **Deployment**: Flask REST API

## 🚀 How to Run This Project Locally (Step-by-Step Guide)

Follow the steps below to run the full crop recommendation system on your machine.

## 🚀 Getting Started

# STEP 1: Clone the project from GitHub
git clone https://github.com/AyushiButani/recommendation-system.git
cd recommendation-system

# STEP 2: Set up and run the backend (Flask API)
cd src/django-ML-API

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate        # For macOS/Linux
venv\Scripts\activate           # For Windows

# Install required Python packages
pip install -r requirements.txt

# Run the Flask server
python app.py
# Backend will now be running at http://localhost:5000

# STEP 3: Run the frontend (React app)
cd ../..                        # Go back to the root project directory
npm install                    # Install frontend dependencies
npm start                      # Start the React development server

# The frontend will now run at http://localhost:3000


## 📸 Sample Prediction Output

> **Input:**  
> N = 90, P = 42, K = 43, Temp = 21.2°C, Humidity = 82%, pH = 6.5, Rainfall = 202 mm  
 
 **Predicted Crop:** 🌾 Rice

👥 Acknowledgment

Originally developed by our team and hosted by @dinesh250-star.
This version is forked to highlight my contributions in data science and ML deployment.

## 📫 Contact

Feel free to reach out for **data science internships**, or to learn more about my work:

📧 ayushibutani9@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-butani/)  
🌐 [GitHub](https://github.com/AyushiButani)




