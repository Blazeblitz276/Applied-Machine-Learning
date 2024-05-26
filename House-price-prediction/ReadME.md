
# House-price-prediction

This section focuses on predicting house prices in Sydney using regression models.


### Directory Structure
```
House-Price-Prediction/
├── data
│ ├── Sydney_house_data.csv
├── House_Price_Prediction.ipynb
└──  README.md
```

## Dataset

The dataset used is `Sydney_house_data.csv` which can be obtained from [Kaggle](https://www.kaggle.com/shree1992/housedata).

## Tasks

1. **Data Preprocessing:** Determine continuous and categorical features, handle missing values.
2. **Univariate Analysis:** Visualize the distribution of each continuous variable and the target.
3. **Feature Dependency Analysis:** Plot 2D scatter plots of the target vs. each continuous feature.
4. **Model Evaluation:** Train and evaluate Linear Regression, Ridge, Lasso, and Elasticnet models.

## Requirements

- pandas
- numpy
- scikit-learn
- matplotlib

## How to Run

1. Install the required packages:
```bash
pip install -r requirements.txt
```
Run the Jupyter Notebook:
```bash
jupyter notebook House_price_prediction.ipynb
```
