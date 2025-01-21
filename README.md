# Credit Card Fraud Detection

This project involves detecting fraudulent credit card transactions using a Random Forest Classifier. It uses a dataset of transactions, each labeled as either fraudulent or valid.

## Dataset

The dataset used for this project contains credit card transactions, with the following main features:
- `Time`: The seconds elapsed between this transaction and the first transaction in the dataset.
- `V1` to `V28`: The result of a PCA transformation.
- `Amount`: The transaction amount.
- `Class`: The label (1 for fraudulent transactions and 0 for valid transactions).

The dataset is assumed to be stored in a CSV file named `creditcard.csv`.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install the required packages using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
Project Structure
Credit_Card_Fraud_Detection.py: Main script to load, preprocess, train, and evaluate the Random Forest Classifier on the dataset.
creditcard.csv: The dataset file (not included in the repository; must be added separately).
Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your_username/credit-card-fraud-detection.git
Navigate to the project directory:

bash
Copy
Edit
cd credit-card-fraud-detection
Place the creditcard.csv file in the project directory.

Run the script to train and evaluate the model:

bash
Copy
Edit
python Credit_Card_Fraud_Detection.py
The script will output performance metrics such as accuracy, precision, recall, F1-Score, and Matthews correlation coefficient. It will also display a heatmap of the correlation matrix and the confusion matrix.

Results
The project evaluates the Random Forest Classifier's performance in detecting fraudulent transactions. It uses metrics like accuracy, precision, recall, F1-Score, and Matthews correlation coefficient for evaluation. A confusion matrix is also provided for detailed insight into the model's performance.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or new features.
