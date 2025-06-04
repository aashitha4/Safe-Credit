# Credit Card Fraud Detection 💳

This project implements a machine learning pipeline to detect fraudulent credit card transactions using a Decision Tree classifier. The notebook covers data preprocessing, dynamic feature selection, hyperparameter tuning with GridSearchCV, and model evaluation.

## ✨ Features

*   **Data Preprocessing**: Handles missing values and scales the 'Amount' feature.
*   **Dynamic Feature Selection**: Uses `SelectKBest` to identify the most relevant features.
*   **Model Training**: Employs a `DecisionTreeClassifier`.
*   **Hyperparameter Optimization**: Utilizes `GridSearchCV` to find the best model parameters.
*   **Evaluation**: Assesses model performance using Accuracy, Confusion Matrix, and Classification Report.
*   **Visualization**: Includes plots for Feature Importance and Confusion Matrix.

## 📊 Dataset

The notebook processes a credit card transaction dataset (e.g., `archive (3).zip` from the notebook) which typically contains PCA-transformed features (V1-V28), 'Time', 'Amount', and a 'Class' label (0 for non-fraud, 1 for fraud).

*Update the path `'/content/archive (3).zip'` in the notebook if your dataset is located elsewhere or named differently.*

## 🛠️ Requirements

*   Python 3
*   NumPy
*   Pandas
*   Matplotlib
*   Seaborn
*   Scikit-learn

You can install these dependencies using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter