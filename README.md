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

-This project strengthened my skills in **machine learning, model deployment, Flask APIs, and full-stack integration** — all of which are highly relevant for data science internships.


## 🛠️ Tech Stack

- **Frontend**: React.js, CSS
- **Backend**: Python, Flask
- **ML Tools**: Pandas, Scikit-learn, Seaborn, Matplotlib
- **Deployment**: Flask REST API

## 🚀 How to Run This Project Locally

Follow the steps below to set up and run the full crop recommendation system on your machine.

---

### 🔁 Clone the Repository

```bash
git clone https://github.com/AyushiButani/recommendation-system.git
cd recommendation-system


### 🧠 Set Up the Backend (Flask API)

```bash
cd src/django-ML-API

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows

# Install dependencies
pip install -r requirements.txt

# Run backend
python app.py

###🖥️ Run the Frontend (React App)

cd ../..         # Go back to root folder
npm install      # Install frontend dependencies
npm start        # Start React app


👥 Acknowledgment

Originally developed by our team and hosted by @dinesh250-star.
This version is forked to highlight my contributions in data science and ML deployment.

## 📫 Contact

Feel free to reach out for **data science internships**, or to learn more about my work:

📧 ayushibutani9@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-butani/)  
🌐 [GitHub](https://github.com/AyushiButani)




