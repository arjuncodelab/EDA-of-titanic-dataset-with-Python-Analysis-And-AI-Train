# Titanic Survival Prediction | EDA & Machine Learning
## Project Overview
This project explores the Titanic dataset using Exploratory Data Analysis (EDA) and Machine Learning to understand the factors influencing passenger survival.

A Random Forest Classifier is developed to predict passenger survival based on demographic and travel-related features.

## Objectives
- Perform data cleaning and handle missing values.
- Optimize memory usage through data type conversion.
- Conduct feature selection and correlation analysis.
- Detect and remove outliers using the IQR method.
- Perform feature engineering.
- Analyze survival rates across different passenger groups.
- Build and evaluate a Random Forest classification model.

### Dataset (link)[https://www.kaggle.com/c/titanic/data?select=train.csv]
The project uses titanic.csv, containing passenger information such as:
  - Age and Sex
  - Passenger Class
  - Fare
  - Family Members (SibSp and Parch)
  - Embarkation Port
  - Survival Status (Target Variable)

### Analysis & Methodology
- Data Cleaning: Handle missing values and remove unnecessary columns.
- Memory Optimization: Convert data types to reduce memory usage.
- Feature Selection: Apply SelectKBest with ANOVA F-test.
- EDA: Explore distributions, correlations, and survival patterns.
- Outlier Handling: Apply the IQR method to Age and Fare.
- Feature Engineering: Create Age Group, Fare Group, Family Size, and IsAlone features.
- Model Building: Train a Random Forest Classifier.
- Model Evaluation: Evaluate using Accuracy, ROC-AUC, Classification Report, Confusion Matrix, and ROC Curve.

### Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```
Titanic-Survival-Analysis/
│
├── titanic.csv
├── Titanic_EDA.ipynb
└── README.md
```
### How to Run
- Clone the repository:

```
bash
git clone https://github.com/your-username/Titanic-Survival-Analysis.git
Install dependencies:
```
```
bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
Run Jupyter Notebook:
```
```
bash
jupyter notebook
Open Titanic_EDA.ipynb and run the cells.
```
## Key Findings
- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers generally had better survival outcomes.
- Higher fares were associated with better survival rates.
- Age and family size also showed relationships with survival.

###Future Improvements.
- Compare multiple classification algorithms.
- Perform hyperparameter tuning.
- Implement cross-validation.
- Use pipelines to prevent data leakage.

## Conclusion
This project demonstrates an end-to-end data analysis and machine learning workflow, covering data preprocessing, visualization, feature engineering, and predictive modelling using the Titanic dataset.
