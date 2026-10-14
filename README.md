# Diabetes Classification using Gaussian Discriminant Analysis (GDA)

## Project Overview

This project explores generative classification methods for a diabetes-related classification task using Gaussian Discriminant Analysis (GDA), Linear Discriminant Analysis (LDA), and Logistic Regression.

The project covers probability distributions, feature exploration, classification boundaries, model assumptions, and medical-style performance evaluation.

## Dataset

- **Source:** `sklearn.datasets.load_diabetes`
- **Dataset:** Diabetes dataset provided by scikit-learn
- **Task:** Binary classification using a derived target

**Important:** The built-in scikit-learn diabetes dataset is originally designed for regression, not diabetes diagnosis. The binary classes created for this project are derived from its continuous target and do not represent an official clinical diagnosis.

## Objectives

- Explore dataset features and class distributions.
- Visualize feature histograms by class.
- Analyze correlations between features.
- Implement the multivariate Gaussian probability density function.
- Visualize Gaussian distributions with different means and covariance matrices.
- Implement Linear Discriminant Analysis (LDA).
- Visualize a linear decision boundary using two features.
- Evaluate classification performance using medical-style metrics.
- Analyze false positives versus false negatives.
- Explore decision threshold optimization.
- Test LDA's equal-covariance assumption.
- Compare LDA with Logistic Regression.

## Methodology

1. Load and inspect the diabetes dataset.
2. Create a documented binary classification target.
3. Perform exploratory data analysis (EDA).
4. Plot feature distributions and correlation matrices.
5. Implement and visualize the multivariate Gaussian PDF.
6. Train and evaluate an LDA classifier.
7. Visualize the decision boundary using two selected features.
8. Evaluate sensitivity, specificity, precision, recall, F1-score, and confusion matrix.
9. Analyze decision thresholds and classification errors.
10. Compare LDA with Logistic Regression and discuss model assumptions.

## Technologies Used

- Python
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

## Project Structure

```text
gaussian-discriminant-analysis-diabetes/
├── main.ipynb
├── README.md
└── requirements.txt
```

## Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/sabarish-1012/gaussian-discriminant-analysis-diabetes.git
```

### 2. Navigate to the project folder

```bash
cd gaussian-discriminant-analysis-diabetes
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `main.ipynb` and run the cells in order.

## Evaluation Metrics

- **Sensitivity (Recall):** Measures how many actual positive-class cases are correctly identified.
- **Specificity:** Measures how many actual negative-class cases are correctly identified.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **F1-score:** Balances precision and recall.
- **Confusion Matrix:** Summarizes true positives, true negatives, false positives, and false negatives.
- **Threshold Analysis:** Examines how changing the decision threshold affects classification performance.

## Key Learning Outcomes

- Understanding generative classification and Gaussian distributions.
- Understanding LDA and its shared-covariance assumption.
- Visualizing decision boundaries.
- Evaluating classification models beyond accuracy.
- Understanding the trade-off between false positives and false negatives.
- Comparing generative and discriminative approaches.

## Limitations

This is an educational machine-learning project. The dataset and derived labels do not constitute a validated diabetes diagnosis. Model predictions must not be used for real clinical decisions.

## Author

**Sabarish**

GitHub: https://github.com/sabarish-1012