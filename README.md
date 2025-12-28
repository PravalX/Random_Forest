🍷 Wine Quality Analysis using Machine Learning

📌 Project Overview

This project focuses on analyzing the Wine Quality Dataset to understand how various physicochemical properties influence wine quality. Statistical analysis and machine learning models are used to extract insights and predict wine quality. The project was completed as part of FINLATICS – Enabling Insights and includes exploratory data analysis, correlation studies, and predictive modeling.

🎯 Objectives

The key goals of this project are:
Identify the most frequently occurring wine quality
Analyze correlations between wine quality and:
Fixed acidity
Alcohol content
Free sulfur dioxide
Volatile acidity
Compare residual sugar levels for the best and worst quality wines
Build and compare Decision Tree and Random Forest models for wine quality prediction

📊 Dataset

Dataset: Wine Quality Dataset
Target Variable: quality
Features Include:
Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol

🔍 Key Findings

1️⃣ Wine Quality Distribution
Most frequent wine quality: 5
Highest quality value: 8
Lowest quality value: 3

2️⃣ Correlation Analysis
Feature	Correlation with Quality	Interpretation
Fixed Acidity	+0.12	Weak positive correlation
Alcohol	+0.47	Moderate positive correlation
Free Sulfur Dioxide	-0.05	Weak negative correlation
Volatile Acidity	-0.39	Weak to moderate negative correlation

📌 Insight:

Higher alcohol content generally corresponds to better wine quality
Increased volatile acidity tends to reduce wine quality

3️⃣ Residual Sugar Analysis
Lowest quality wine (Quality = 3): ~2.63
Highest quality wine (Quality = 8): ~2.58
Residual sugar does not show a strong impact on quality.

🤖 Machine Learning Models

🌳 Decision Tree Classifier
Performs well for Quality 5 and 6
Poor classification for minority classes (3, 4, 8)

Accuracy: 60.5%

🌲 Random Forest Classifier
Better generalization than Decision Tree
Improved performance for dominant classes
Still struggles with underrepresented quality labels

Accuracy: 67.5%

📌 Conclusion:

Random Forest outperforms the Decision Tree model in predicting wine quality.

📈 Model Comparison

Model	Accuracy
Decision Tree	60.5%
Random Forest	67.5%

🛠️ Technologies Used

Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn
