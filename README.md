# CardioSense AI For Heart Disease Prediction

A clinical heart disease prediction application built on an ensemble of 5 machine learning models,
developed for the Kaggle Playground Series Season 6 Episode 2 competition.

## Models
- Bagging (Decision Tree base)
- AdaBoost
- Gradient Boosting
- XGBoost (best single model — 0.88544 ROC-AUC)
- Stacking (LR + RandomForest + GB → LR meta-learner)

## Features
- 🫀 Single patient risk prediction with probability score
- 📊 Full model comparison dashboard (ROC curves, metrics, speed vs performance)
- 🔬 Per-model deep dive (confusion matrix, feature importance, classification report)
- 📈 Data insights (correlation heatmap, feature distributions, class analysis)

## Tech Stack
Python · Streamlit · XGBoost · Scikit-learn · Pandas · Matplotlib · Seaborn

## Competition
Kaggle Playground Series S6E2 — Heart Disease Classification

## Run Locally
pip install -r requirements.txt
streamlit run app.py
