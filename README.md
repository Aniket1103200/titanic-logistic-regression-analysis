# Titanic Survival Prediction – Logistic Regression

Predicts whether a Titanic passenger **survived**, using passenger data such as class, sex, age, fare and family on board.

> 📚 **Course-based project:** built while following the Udemy course *Python for Data Science and Machine Learning Bootcamp* (Pierian Data), using a semi-cleaned version of the Kaggle Titanic dataset.

## Approach
1. Exploratory analysis: survival by sex and passenger class, age distribution, missing data (Seaborn)
2. Data cleaning: filled missing ages, dropped columns with too many gaps, and turned categories into dummy variables
3. Trained a **logistic regression** model (scikit-learn)
4. Evaluated with a classification report and a confusion matrix

## Results (test set: 267 passengers)

| Metric | Value |
|---|---|
| Accuracy | **0.83** |
| Macro F1 | 0.81 |

## Tech
Python · pandas · NumPy · scikit-learn · Matplotlib · Seaborn · Jupyter

## Run it
```bash
git clone https://github.com/Aniket1103200/titanic-logistic-regression-analysis.git
cd titanic-logistic-regression-analysis
pip install -r requirements.txt
jupyter notebook Titanic_Project.ipynb
```
