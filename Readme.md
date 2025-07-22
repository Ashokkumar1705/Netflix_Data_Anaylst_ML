Netflix Content Analysis & ML Prediction
A comprehensive data science and machine learning project using Netflix's dataset to analyze trends in global content and build a predictive model with 99.8% accuracy.

📌 Table of Contents
Project Overview

Dataset

Exploratory Data Analysis

Machine Learning Model

Performance & Evaluation

Key Insights

Technologies Used

How to Run

Conclusion

Author

🔍 Project Overview
This project explores over 8,800 Netflix titles to extract insights about:

Genre distribution and popularity

Content trends across countries and years

Target audience breakdown

Predicting attributes using a machine learning classification model

📂 Dataset
📁 Source: Kaggle / Netflix Datasets

💡 Rows: 8,800+ titles

🧾 Features: Title, Type, Genre, Country, Target Age, Duration, Rating, Date Added, etc.

📊 Exploratory Data Analysis
Movies vs. TV Shows: ~70% are Movies, 30% are TV Shows

Top Genres: International Movies, Dramas, Comedies, International TV Shows

Leading Countries: United States, India, UK, South Korea

Target Audiences: Children's content, Teen-friendly shows, and Adult programs are well-balanced

📈 Chart examples included in the notebook:

Content over years

Genre word clouds

Age distribution

Top countries

Machine Learning Model
We trained a classification model to predict a key attribute based on content metadata (genre, country, duration, etc.).

Algorithm Used
Random Forest Classifier

Feature Selection
Genre, Target Age, Country, Duration, Release Year, and more

📈 Performance & Evaluation
✅ Accuracy: 99.77%
📉 Confusion Matrix:
Predicted 0	Predicted 1
Actual 0	1,836	2
Actual 1	4	801
📄 Classification Report:
Class	Precision	Recall	F1-score	Support
0	1.00	1.00	1.00	1,838
1	1.00	1.00	1.00	805
🟢 Model Strengths
Exceptionally high accuracy: 99.77%

Balanced performance: No class imbalance issues

Low false positives/negatives: Only 6 total misclassifications

Strong feature engineering for categorical data

💡 Key Insights
Netflix's content is globally diverse and targets multiple age groups

Clear genre preferences and release year trends help enhance recommendation engines

ML models can accurately predict content types or target demographics with structured metadata

🛠 Technologies Used
Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn

Jupyter Notebooks

🚀 How to Run
Clone the repository:

bash
git clone https://github.com/yourusername/netflix-data-analysis.git
cd netflix-data-analysis
Open Jupyter Notebook:

bash
jupyter notebook Netflix_EDA_ML.ipynb
Run cells to explore EDA, charts, and model evaluation.

Conclusion

This project demonstrates:

Strong exploratory data analysis skills

Hands-on experience with classification models

Clean feature engineering of categorical and mixed data types

Practical implementation with insight generation

✅ Use this notebook to build recommendations, dashboards, or extend it for deep learning tasks!

