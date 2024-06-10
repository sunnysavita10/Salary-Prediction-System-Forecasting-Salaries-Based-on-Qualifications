# Salary Prediction Model

This repository contains a Python script for predicting salaries based on years of experience, test scores, and interview scores. The script trains a linear regression model on the provided dataset and saves the trained model for future use.

## Introduction
Salary prediction is a common task in human resources and recruitment. Employers often need to estimate salaries for new hires based on their qualifications and experience. This project aims to build a predictive model that can accurately estimate salaries using relevant features such as years of experience, test scores, and interview scores.

## Dataset
The dataset used in this project (`hiring.csv`) contains information about candidates' years of experience, test scores, interview scores, and corresponding salaries. It is used to train and evaluate the predictive model.

## Model Training
- The script preprocesses the dataset by filling missing values and converting categorical values to numerical values.
- A linear regression model is trained using the preprocessed data to predict salaries based on the input features.
- The trained model is saved to disk for future use.

## Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/salary-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd salary-prediction
    ```
3. Run the script:
    ```bash
    python salary_prediction.py
    ```

## Requirements
- Python 3.x
- Libraries: numpy, pandas, matplotlib, scikit-learn

You can install the required libraries using the following command:
```bash
pip install numpy pandas matplotlib scikit-learn
```
