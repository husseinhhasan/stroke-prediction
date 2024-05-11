# Stroke Prediction Machine Learning Application

## Overview
This machine learning application predicts whether an individual has had a stroke based on several parameters using the XGBoost model. The project was developed as part of a Kaggle competition. The dataset includes various features such as age, gender, hypertension, heart disease, average glucose level, BMI, smoking status, and more.

## Files
- **main.py**: Python script containing the code for data preprocessing, model training, and prediction.
- **model.pkl**: Pre-trained XGBoost model saved as a pickle file.
- **data/**
  - **train1.csv**: Training data file 1.
  - **train2.csv**: Training data file 2.
  - **test.csv**: Test data file.
  - **submission.csv**: Submission file for the Kaggle competition.

## Usage
1. **Data Preparation**: Ensure that the training and test data files (`train1.csv`, `train2.csv`, `test.csv`) are available in the `data/` directory.
2. **Model Training**: Run the `main.py` script to preprocess the data, train the XGBoost model, and generate predictions.
3. **Prediction**: After model training, the script will generate predictions for the test data and save the results in `submission.csv`.
4. **Evaluation**: Evaluate the performance of the model using appropriate metrics such as accuracy, precision, recall, and F1-score.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- xgboost

## License
This project is licensed under the [MIT License](LICENSE).

