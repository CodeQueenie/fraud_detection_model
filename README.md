# Fraud Detection Model
This project trains a machine learning model to detect fraudulent transactions using a logistic regression algorithm.

## Dataset
The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

### Instructions to Get the Dataset
1. Download the dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).
2. Extract the files `fraudTrain.csv` and `fraudTest.csv`.
3. Place the files in the `data/` folder of the project directory:

## Requirements
- Python 3.9
- Libraries: pandas, scikit-learn, joblib

## Instructions
1. Place the dataset files (`fraudTrain.csv` and `fraudTest.csv`) in the `data/` folder.
2. Navigate to the `src` folder:
   ```bash
   cd src
3. Run the training script:
   ```bash
   python train_model.py

## Output
- The trained model is saved in the outputs/ folder as fraud_model.pkl.

## Usage
- To train the model, run the following command:
  ```bash
  python train_model.py

## Expected Output
- The script will output the following:
 - A confusion matrix and classification report printed in the terminal.
 - Example:
   ```lua
   Confusion Matrix:
    [[100  10]
    [  5  20]]

    Classification Report:
             precision    recall  f1-score   support
     0       0.95      0.90      0.92       110
     1       0.67      0.80      0.73        25