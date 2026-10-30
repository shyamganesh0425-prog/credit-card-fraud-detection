# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project uses Machine Learning to identify potentially fraudulent credit card transactions. It compares Logistic Regression and Random Forest models to understand their performance in detecting fraud.

## Dataset
- Dataset: Credit Card Fraud Detection
- Total transactions: 284,807
- Normal transactions: 284,315
- Fraudulent transactions: 492
- Features: 30
- Target column: `Class`
  - `0` = Normal transaction
  - `1` = Fraudulent transaction

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Joblib

## Project Workflow
1. Load and explore the dataset.
2. Check missing values and class distribution.
3. Split the dataset into training and testing sets.
4. Train a Logistic Regression model.
5. Train a Random Forest model.
6. Evaluate both models using precision, recall, F1-score, and ROC-AUC.
7. Visualize important features.
8. Save the trained Random Forest model.

## Model Results

### Logistic Regression
- Precision for fraud: approximately 6.1%
- Recall for fraud: approximately 91.8%
- F1-score for fraud: approximately 11.4%

### Random Forest
- Precision for fraud: approximately 90.6%
- Recall for fraud: approximately 78.6%
- F1-score for fraud: approximately 84.2%
- ROC-AUC: approximately 0.9573

These results come from the project's test set. The models have different trade-offs: Logistic Regression detects more fraudulent transactions but produces more false alarms, while Random Forest produces fewer false alarms but misses more fraudulent transactions.

## Project Files
- `Untitled.ipynb` — Jupyter Notebook containing the analysis and model training.
- `creditcard.csv` — Dataset used for training and evaluation.
- `fraud_detection_model.pkl` — Saved Random Forest model.

## How to Run
1. Install Python.
2. Install the required libraries:

   `pip install pandas matplotlib scikit-learn joblib`

3. Open the Jupyter Notebook.
4. Run the notebook cells in order.

## Disclaimer
This is an educational Machine Learning project. Its results do not guarantee reliable fraud detection in real-world financial systems.