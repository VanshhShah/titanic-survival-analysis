# Titanic Survival Analysis

learning how ML works and saw many people started with this so i did too

## Dataset

Source: Kaggle (https://www.kaggle.com/competitions/titanic)
Target: `Survived` (0 = No, 1 = Yes)

1. **Data cleaning**: handled missing values in `Age`, `Cabin` and `Embarked`
2. **EDA**: univariate and bivariate analysis, correlation heatmap
3. **Feature engineering**: [family size, title extracted from name, age groups]
4. **Modeling**: trained [Logistic Regression] and compared accuracy

## Model Results

accuracy on training data: 80.75%
accuracy on test data: 78.21%

## Tech Stack

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/VanshhShah/titanic-survival-analysis.git
cd titanic-survival-analysis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook titanic_analysis.ipynb
```
