# Titanic Survival Prediction and EDA

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset and builds a Machine Learning model to predict passenger survival.

## Dataset
- train.csv – Training dataset
- test.csv – Testing dataset

## Exploratory Data Analysis

### Dataset Information
- Total Records: 891
- Features: 12

### Missing Values Analysis
- Age: 177 missing values
- Cabin: 687 missing values
- Embarked: 2 missing values

### Visualizations Performed
1. Survival Distribution
2. Survival by Gender
3. Survival by Passenger Class
4. Age Distribution
5. Correlation Heatmap

## Key Findings
- Female passengers had a higher survival rate than male passengers.
- First-class passengers were more likely to survive.
- Most passengers were between 20 and 40 years old.
- Passenger class and fare significantly influenced survival.
- Missing values were handled during preprocessing.

## Machine Learning Model
- Algorithm: Random Forest Classifier
- Hyperparameter tuning performed using GridSearchCV.

## Model Performance
- Accuracy: 82.12%

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Files
- notebook.ipynb
- train.csv
- test.csv
- predictions.csv
- README.md

## Conclusion
The analysis identified important factors affecting passenger survival and demonstrated how machine learning can be used to predict survival outcomes.
