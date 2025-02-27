# Credit Card Fraud Detection

## Overview
This project aims to detect fraudulent credit card transactions using machine learning. The dataset is highly imbalanced, meaning fraudulent transactions are significantly fewer than normal transactions. The notebook explores statistical measures, data preprocessing, and model training to improve fraud detection accuracy.

## Dataset
The dataset contains transactions labeled as:
- `0` = Normal Transaction
- `1` = Fraudulent Transaction

The project also applies **undersampling** to handle class imbalance.

## Technologies & Libraries Used
The following Python libraries were used:
- `numpy` (Numerical computing)
- `pandas` (Data manipulation and analysis)
- `sklearn.model_selection` (Train-test split)
- `sklearn.linear_model.LogisticRegression` (Machine Learning Model)
- `sklearn.metrics.accuracy_score` (Model Evaluation)

## Usage Instructions
1. Open Google Colab.
2. Upload the `CreditCardFraudDetection.ipynb` file.
3. Run the notebook cell by cell.
4. Ensure you have the required libraries installed using:
   ```python
   !pip install numpy pandas scikit-learn
   ```
5. Follow the steps in the notebook to preprocess data, train the model, and evaluate performance.

## Model Training & Evaluation
- The dataset is split into **training** and **testing** sets.
- A **Logistic Regression** model is used for fraud detection.
- The model's performance is evaluated using **accuracy score**.

## Results & Findings
- Fraudulent transactions have different statistical properties than normal ones.
- Undersampling helps balance the dataset but may reduce overall transaction diversity.
- The trained model achieves a certain accuracy in detecting fraudulent transactions.

## Author
This project was implemented on **Google Colab** as part of a credit card fraud detection initiative.

## License
This project is open-source and available for further improvements and modifications.

