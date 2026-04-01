# Credit Fraud Detection

## Project Description
This project focuses on detecting credit card fraud using machine learning techniques. Fraud detection is crucial in preventing financial losses and ensuring the integrity of the financial system.

## Dataset Details
The dataset used in this project is highly imbalanced, containing transactions made by credit cards in September 2013 by European cardholders. The dataset can be obtained from Kaggle or similar platforms. The primary features in the dataset include:
- `Time`: The number of seconds elapsed between this transaction and the first transaction in the dataset.
- `V1, V2, ..., V28`: These are the result of a PCA transformation, representing various features about the transaction.
- `Amount`: The transaction amount.
- `Class`: This represents whether the transaction is fraudulent (1) or legitimate (0).

## Methodology
1. **Data Preprocessing**: The data was cleaned and normalized, with specific attention given to handling any missing or inconsistent data points.
2. **Exploratory Data Analysis**: Visualizations and statistical analysis were conducted to understand the distributions of features and the prevalence of fraud.
3. **Model Selection**: Multiple models were tested, including Logistic Regression, Random Forest, and Gradient Boosting.
4. **Evaluation Metrics**: Model performance was evaluated using metrics such as accuracy, precision, recall, and the F1 score, specifically focusing on the model’s ability to detect fraudulent transactions.

## Model Performance
The best-performing model achieved an accuracy of XX% and a recall of YY%, significantly outperforming traditional methods in detecting fraud. Detailed performance metrics can be found in the analysis notebook.

## Installation Instructions
To install the required libraries, use the following command:
```bash
pip install -r requirements.txt
```

## Usage Guide
- Load the dataset and preprocess it as described in the notebook.
- Train the model using the command:
```python
python train_model.py
```
- Evaluate the model with:
```python
evaluate_model.py
```
For detailed usage, refer to the Credit_Fraud.ipynb notebook.

## License
This project is licensed under the MIT License.