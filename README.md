# Sales Prediction Using Python 📈

This repository contains a machine learning project focused on predicting sales based on advertising expenditures across different platforms. The goal of this project is to use linear regression to forecast sales based on the amount spent on TV, Radio, and Newspaper ads.

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Code and Analysis](#code-and-analysis)
5. [Results](#results)
6. [How to Run](#how-to-run)
7. [License](#license)

## Project Description
Sales prediction is crucial for businesses to optimize their advertising strategies and budget. In this project, we build a **Linear Regression** model to predict sales based on advertising costs.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/sales-prediction-python.git
    ```
2. Navigate into the project directory:
    ```bash
    cd sales-prediction-python
    ```
3. Install the required Python libraries using:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset
The dataset used for this project is the **Advertising.csv** which contains data on advertising spend and corresponding sales figures.

- **Dataset Name**: `Advertising.csv`
- [Download the Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)

## Code and Analysis
The notebook (`.ipynb`) and Python script (`.py`) files include the code used for:
- Loading and exploring the dataset.
- Performing feature engineering and checking for missing values.
- Training a Linear Regression model.
- Evaluating model performance and visualizing results.

## Results
Key results from the analysis include:
- **Model Evaluation Metrics**:
    - Mean Squared Error: `{{ mse }}`
    - R^2 Score: `{{ r2 }}`
- **Visualization**:
    - Actual Sales vs Predicted Sales:
    ![Actual vs Predicted Sales](sales_prediction_plot.png)

## How to Run
1. To run the project, open the `sales_prediction.ipynb` file in Google Colab or Jupyter Notebook and execute the cells step-by-step.
2. If using the Python script:
    ```bash
    python sales_prediction.py
    ```

Make sure the dataset (`Advertising.csv`) is in the same directory as the notebook or script.

## License
This project is licensed under the MIT License.
