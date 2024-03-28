

# ACME Happiness Survey :

## Overview

This report encapsulates the methodology, analysis, and findings from the Happiness Survey. Aimed at identifying factors influencing happiness among participants, this study leverages data preprocessing, exploratory data analysis (EDA), predictive modeling, and evaluation metrics to draw insights and predict happiness levels.

## Dataset

The dataset comprises responses from 126 participants, each providing answers to six survey questions (X1 to X6) on a Likert scale, along with their reported happiness state (Y).

## Analysis Pipeline

### 1. **Importing Libraries**

- **Data Manipulation**: `Pandas`, `NumPy`
- **Visualization**: `Seaborn`, `Matplotlib`
- **Machine Learning**: `Scikit-learn`, `Imbalanced-learn`

### 2. **Data Preprocessing**

- **Encoding Categorical Variables**: Conversion of categorical responses to numeric codes.
- **Feature Scaling**: Normalization of feature variables to ensure uniformity.
- **Handling Class Imbalance**: Application of SMOTE to balance the distribution of target classes.

### 3. **Exploratory Data Analysis (EDA)**

- **Distribution Analysis**: Examination of the distribution of survey responses.
- **Correlation Analysis**: Identification of relationships between survey questions and happiness levels.

### 4. **Predictive Modeling**

- **Model Selection**: Logistic Regression, Random Forest, and Gradient Boosting Classifier.
- **Model Training**: Application of cross-validation and grid search for hyperparameter tuning.
- **Model Evaluation**: Use of F1 score and accuracy as primary metrics for performance assessment.

## Key Findings

- Certain survey questions are strong predictors of happiness.
- Predictive models demonstrate robustness in forecasting happiness levels, with Gradient Boosting showing the most promise.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Libraries

Install the required Python libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn
```

### Execution

1. Clone the repository or download the Jupyter Notebook and dataset.
2. Open the notebook in Jupyter Notebook or Jupyter Lab.
3. Execute the cells sequentially to replicate the analysis.

## Conclusion

This technical report provides a comprehensive overview of the steps taken to analyze the ACME Happiness Survey . Through methodical preprocessing, insightful EDA, and predictive modeling, we have identified key factors influencing happiness and developed models capable of predicting happiness levels with considerable accuracy.

## AI Assistance Notice
AI provided support with Portions of coding, documentation and ideation
