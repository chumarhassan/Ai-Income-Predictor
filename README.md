🧩 Introduction

AI Income Predictor is a machine learning-powered desktop app that predicts whether a user's income is likely to be <= $50K or > $50K per year based on demographic and socio-economic inputs. It offers insightful recommendations and visualizations to help users understand and potentially improve their income profile.

✨ Features

- Income Prediction using ML
- User-Friendly GUI (Tkinter)
- Visualizations: feature importance, histograms, confusion matrix
- Confidence Score and estimated income range
- Personalized recommendations
- Prediction history storage
- Dark mode GUI

🔍 How It Works

- Data Cleaning: handles missing values and encodes categoricals
- Model: Random Forest Classifier (trained with GridSearchCV)
- Prediction: Provides probability and estimated income bracket
- Recommendations: Rule-based tips based on user input and feature impact

⚙️ Installation

1. Clone the repo: git clone https://github.com/chumarhassan/AI-Income-Predictor.git
2. Create and activate virtual environment
3. Install packages: pandas, numpy, scikit-learn, matplotlib, seaborn
4. Download and place adult.csv in project root

🚀 Usage

Run: python income_predictor.py
- Input data via GUI
- Click "Predict My Income"
- View prediction, probability, and recommendations

📁 Project Structure

- adult.csv: dataset
- income_model.pkl: trained model
- prediction_history.csv: local prediction logs
- main.py: main application script

📊 Data Source

Uses the Adult Income Dataset from the Kaggle.

📉 Visualizations

- Feature Importance
- Probability Histogram
- Confusion Matrix
- Correlation Heatmap
- Cumulative Probability Plot

⚠️ Limitations

- Static dataset (no real-time updates)
- Rule-based AI recommendations
- Desktop-only application
- Generalization limited by training data

🚧 Future Enhancements

- Web version with user accounts
- LLM-powered recommendations
- Live economic/job market data via APIs
- Expanded prediction ranges
- UI/UX improvements

🤝 Contributing

1. Fork repo
2. Create branch: git checkout -b feature/YourFeatureName
3. Commit: git commit -m "Add feature"
4. Push and open Pull Request


📬 Contact

Umar Hassan  
Email: chumarhassan999@gmail.com  
GitHub: https://github.com/chumarhassan

