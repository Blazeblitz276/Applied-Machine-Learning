
# Credit-risk-classification

This section focuses on classifying credit risk using various classification models.


### Directory Structure
```
Credit-Risk-Classification/
├── data
│ ├── dataset_31_credit-g.arff
├── Credit_Risk_Classification.ipynb
└──  README.md
```
## Dataset

The dataset used is the 'credit-g' dataset, which can be obtained using the command `fetch_openml('credit-g')` from [OpenML](https://www.openml.org/d/31).

## Tasks

1. **Data Preprocessing:** Determine continuous and categorical features, handle missing values.
2. **Univariate Analysis:** Visualize the distribution of each continuous variable and the target.
3. **Initial Model Evaluation:** Train and evaluate a Logistic Regression model.
4. **Comparative Model Evaluation:** Compare Logistic Regression, Linear SVM, and K-Nearest Neighbors models.

## Requirements

- pandas
- numpy
- scikit-learn
- matplotlib

## How to Run

1. Install the required packages:
```bash
pip install <requirements>
```
Run the Jupyter Notebook:
```bash
jupyter notebook Credit_risk_classification.ipynb
```
