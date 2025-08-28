# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to build and evaluate models that can accurately identify fraudulent activities from transaction data.

## Overview

- **Problem:** Classify credit card transactions as fraudulent or legitimate.
- **Approach:** Data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.
- **Tech Stack:** Python, pandas, scikit-learn, matplotlib, Jupyter Notebook.

## Dataset

The dataset used is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains anonymized transaction data with features V1-V28, 'Amount', 'Time', and a 'Class' label (1 = fraud, 0 = not fraud).

## Project Structure

```
credit-card-fraud/
│
├── data/                # Raw and processed datasets
├── notebooks/           # Jupyter notebooks for EDA and modeling
├── src/                 # Source code for data processing and modeling
├── outputs/             # Generated reports, figures, and model outputs
└── README.md            # Project documentation
```

## Setup

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/Portfolio-Data-Projects.git
   cd Portfolio-Data-Projects/credit-card-fraud
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Download the dataset and place it in the `data/` directory.

## Usage

- Run exploratory data analysis and model training in the provided Jupyter notebooks in the `notebooks/` folder.
- Modify or extend the code in the `src/` directory for custom experiments.

## Results

- Evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are used to assess model performance.
- The project explores techniques to handle class imbalance, such as undersampling, oversampling, and using appropriate evaluation metrics.

## References

- [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- [Scikit-learn Documentation](https://scikit-learn.org/)

---

_This project is for educational purposes and demonstrates standard approaches to fraud detection using open datasets._
