# Semiconductor Manufacturing Process Analysis

## Project Overview
This project focuses on building a predictive classifier for semiconductor manufacturing yield. By analyzing sensor data and leveraging machine learning, we aim to identify key features impacting production outcomes and enhance process throughput.

---

## Dataset
- **File Name**: `sensor-data.csv`
- **Shape**: 1567 rows, 592 columns
- **Target**:
  - `-1`: Pass
  - `1`: Fail
- Features represent signals from sensors during manufacturing.

---

## Objectives
1. Predict pass/fail outcomes using a machine learning model.
2. Identify the most relevant sensor signals through feature selection.
3. Enhance throughput and reduce costs by focusing on critical production factors.

---

## Steps
### 1. Data Exploration
- Load and examine dataset structure and statistics.
- Check for missing values and target distribution.

### 2. Data Cleansing
- Handle missing data.
- Drop irrelevant features.
- Perform logical modifications to improve data quality.

### 3. Data Analysis & Visualization
- Perform statistical analysis.
- Conduct univariate, bivariate, and multivariate visualizations.

### 4. Data Preprocessing
- Segregate predictors and target.
- Balance classes using SMOTE.
- Perform train-test splitting and standardization.

### 5. Model Training & Evaluation
- Train three supervised models:
  - Random Forest
  - SVM
  - Naive Bayes
- Tune hyperparameters using GridSearchCV.
- Compare models using metrics like accuracy and F1-score.

### 6. Conclusion
- Summarize results.
- Recommend improvements and strategies for future work.

---

## Results
- **Best Model**: Random Forest
- **Accuracy**: High test set performance with robust generalization.
- **Feature Insights**: Identified key signals contributing to yield predictions.

---

## Future Improvements
- Implement real-time prediction and monitoring.
- Incorporate domain knowledge into feature engineering.
- Explore advanced techniques like SHAP for interpretability.

---

## Getting Started
### Prerequisites
- Python 3.7+
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/harshsawant-1/semiconductor-yield-analysis.git
  2. Install dependencies
pip install -r requirements.txt
3. Run the notebook:
jupyter notebook
