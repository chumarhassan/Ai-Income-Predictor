# 🧠 AI Income Predictor

**A desktop application built with Python, Tkinter, and Machine Learning to predict annual income brackets and provide actionable, personalized recommendations.**

---

## 📌 Table of Contents

1. [Introduction](#introduction)  
2. [Features](#features)  
3. [How It Works](#how-it-works)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Project Structure](#project-structure)  
7. [Data Source](#data-source)  
8. [Visualizations](#visualizations)  
9. [Limitations](#limitations)  
10. [Future Enhancements](#future-enhancements)  
11. [Contributing](#contributing)  
12. [Contact](#contact)  

---

## 🧩 Introduction

**AI Income Predictor** is a machine learning-powered desktop app that predicts whether a user's income is likely to be `<= $50K` or `> $50K` per year based on their demographic and socio-economic inputs. It also offers insightful recommendations and visualizations to help users understand and potentially improve their income profile.

---

## ✨ Features

- 🎯 **Income Prediction** using a trained ML model
- 🖼️ **User-Friendly GUI** built with Tkinter (includes dark mode)
- 📊 **Visual Insights**: Feature importance, probability histograms, and confusion matrices
- 📈 **Confidence Score** and estimated income value
- 🔍 **Key Factor Identification** behind predictions
- 🧠 **AI-Powered Recommendations** based on input data
- 💾 **Prediction History** saved locally
- 🔒 **Offline, Desktop-Based App** for privacy and performance

---

## 🔍 How It Works

### 📊 Data Processing
- Uses `adult.csv` dataset from UCI Repository
- Cleans missing values and encodes categorical variables
- Scales features using `StandardScaler`

### 🤖 Machine Learning Model
- Random Forest Classifier with hyperparameter tuning via GridSearchCV
- Trained on cleaned dataset and saved as `income_model.pkl`

### 🧠 Recommendation Logic
- Rule-based recommendations using the model's feature importance
- Personalized suggestions for income improvement

---

## ⚙️ Installation

1. **Clone the repository**
git clone https://github.com/your-username/AI-Income-Predictor.git
cd AI-Income-Predictor
Set up a virtual environment (optional but recommended)
python -m venv venv
# Activate
# Windows:
.\venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn
Add Dataset

Download adult.csv from UCI Repository

Place it in the project root directory

🚀 Usage
python income_predictor.py  # or the name of your main file
🖱️ In-App Flow
Fill out the form with your demographic details

Click "Predict My Income"

View your predicted bracket, confidence, and estimated income

Click "AI Recommendations" for personalized advice

View model performance through visualizations

📁 Project Structure
AI-Income-Predictor/
├── adult.csv               # Dataset
├── income_model.pkl        # Trained ML model
├── prediction_history.csv  # Log of predictions
└── main.py     # Main app file
📊 Data Source
This app uses the Adult Income Dataset from the Kaggle, originally extracted from the 1994 US Census database.

📉 Visualizations
🔍 Feature Importance

📈 Probability Histogram

🔥 Confusion Matrix

🌐 Correlation Heatmap

📊 Cumulative Probability Plot

⚠️ Limitations
Model performance limited by static dataset

Recommendations follow a rule-based system (not conversational AI)

No real-time economic data integration

Works only as a desktop app currently

🚧 Future Enhancements
🌍 Web version with account support

🤖 LLM-powered smart recommendation engine

📡 Live data from APIs (job market, salary insights)

💳 Integration of financial planning and income simulators

📱 Responsive and mobile-ready UI/UX

🤝 Contributing
Contributions are welcome!
# Fork and clone the repo
# Create a feature branch
git checkout -b feature/AmazingFeature
# Commit your changes
git commit -m "Add AmazingFeature"
# Push and open a Pull Request

📬 Contact
Umar Hassan
📧 chumarhassan999@gmail.com
🌐 GitHub Profile
