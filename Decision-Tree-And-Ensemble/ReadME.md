
# Decision-Trees-and-Ensemble

This section focuses on decision trees and ensemble methods such as AdaBoost and Bagging.


### Directory Structure

```
Decision-Trees-and-Ensemble/
├── data
│ ├── letter-recognition.data
│ ├── german.data
│ └── spambase.data
├── Decision_Trees_and_Ensemble.ipynb
└── README.md
```

## Dataset

Three datasets are used in this assignment:

1. **Letter Recognition Dataset:** Contains descriptions of the characters "C" and "G" with 16 attributes.
2. **German Credit Data:** Classifies people as good or bad credit risks based on 20 attributes.
3. **Spam Base Data:** Classifies email messages as spam or ham based on 57 attributes.

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
jupyter notebook Decision_Trees_and_Ensemble.ipynb
```
