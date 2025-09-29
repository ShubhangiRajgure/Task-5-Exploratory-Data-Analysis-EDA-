# Task-5-Exploratory-Data-Analysis-(EDA)
# Titanic Dataset Analysis
📌 Overview

This project explores the Titanic dataset using **Python (Pandas, Matplotlib, Seaborn)**. The dataset contains details of 891 passengers, including demographic, ticket, and survival information. The goal of the analysis is to identify relationships, trends, and survival patterns among passengers.

## 🔍 Methods Used
* Data Exploration
* .info(), .describe(), .value_counts()
* Checked missing values
* Statistical Analysis
* Grouped survival rates by gender, class, and embarkation
* Correlation analysis
* Visualizations
* Histograms: Age distribution
* Boxplots: Age by survival status
* Scatterplots: Age vs Fare with survival color coding
* Heatmap: Correlation matrix
* Pairplot: Key features (Survived, Age, Fare, Pclass)

## 📊 Key Insights
* Survival Rate: ~38% overall.
* Gender: Women had a much higher survival rate than men.
* Class: 1st class passengers survived more, 3rd class the least.
* Age: Children had higher chances of survival.
* Fare: Higher fares correlated with better survival rates.
* Embarkation: Passengers from Cherbourg (C) had higher survival rates compared to Southampton (S).

📁 Project Structure
titanic-analysis/
│
├── titanic.csv              # Dataset
├── analysis.ipynb           # Jupyter Notebook with code & visuals
├── Titanic_Analysis_Report.pdf  # PDF report of findings
└── README.md                # Project documentation

## 🚀 Tools & Libraries
* Python
* Pandas – data manipulation
* Matplotlib & Seaborn – data visualization

## ✅ Conclusion
The Titanic dataset clearly shows that gender, age, and socioeconomic class were strong determinants of survival. Wealthier passengers (1st class, higher fares) and women/children had much better chances of survival.
