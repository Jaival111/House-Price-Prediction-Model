# House-Price-Prediction-Model

This repository contains a machine learning model that predicts house prices based on various input features. The model was built using **Linear Regression** and trained on a dataset of housing data. It has achieved **91% accuracy** on the training set and **90% accuracy** on the test set.

## Project Overview

The goal of this project is to develop a model that can predict house prices based on features such as square footage, number of bedrooms, number of bathrooms, and other relevant attributes. The dataset used for training and testing the model was carefully preprocessed to ensure the highest possible accuracy.

### Key Features:
- **Linear Regression**: The model uses Linear Regression to find the best-fit line that predicts house prices based on input features.
- **Accuracy**: Achieved **91% accuracy** on the training data and **90% accuracy** on the test data.

## Dataset

The dataset contains the following columns:
- `Avg. Area Income`: Average area of the house in square feet.
- `Avg. Area House Age`: Average age of the house in years.
- `Avg. Area Number of Rooms`: Average number of rooms.
- `Avg. Area Number of Bedrooms`: Average number of bedrooms.
- `Area Population` : Population of the area.
- `Address`: Categorical feature representing the location of the house.
- `Price`: The target variable, representing the house price.

> Note: Ensure that the data is clean and free from any missing values before running the model.

## Installation

To run the house price prediction model, you need to have Python installed on your machine along with the necessary dependencies. You can set up the environment using the following steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/house-price-prediction.git
    cd house-price-prediction
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the model for house price prediction, you can refer to the jupyter file:

1. Download and prepare the dataset (if not already included).
2. Run the below script:
    ```bash
    jupyter notebook
    ```

## Model Evaluation

The model was evaluated based on the following metrics:
- **Training Accuracy**: 91%
- **Test Accuracy**: 90%

The model generalizes well to unseen data, indicating that the linear regression approach was effective for this particular dataset.


## Dependencies

The project requires the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

Install all dependencies by running:
```bash
pip install -r requirements.txt


