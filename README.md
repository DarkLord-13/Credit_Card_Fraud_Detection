# Credit Card Fraud Detection

This project aims to detect fraudulent transactions from credit card data using machine learning techniques. The dataset used for this project is highly imbalanced, with a majority of transactions being non-fraudulent.

## Project Overview

The project follows these main steps:
1. **Data Preparation**:
    - Load the dataset.
    - Perform exploratory data analysis.
    - Handle missing values and inspect the dataset.
2. **Data Balancing**:
    - Separate fraudulent and non-fraudulent transactions.
    - Perform under-sampling to balance the dataset.
3. **Model Training**:
    - Split the data into training and testing sets.
    - Train a Logistic Regression model.
4. **Model Evaluation**:
    - Evaluate the model's performance using accuracy metrics.
    - Visualize the results.

## Dependencies

The project requires the following dependencies:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Machine-Learning-01
    ```

3. Install the required packages:
    ```sh
    pip install pandas numpy scikit-learn
    ```

4. Open the Jupyter Notebook `CreditCardFraud.ipynb` and run the cells to execute the project steps:
    ```sh
    jupyter notebook CreditCardFraud.ipynb
    ```

## Usage

1. **Data Preparation**:
    - Load the dataset using Pandas.
    - Perform exploratory data analysis and check for missing values.

2. **Data Balancing**:
    - Separate the dataset into fraudulent and non-fraudulent transactions.
    - Perform under-sampling to create a balanced dataset.

3. **Model Training**:
    - Split the data into training and testing sets using `train_test_split`.
    - Train a Logistic Regression model on the training data.

4. **Model Evaluation**:
    - Evaluate the model's performance using accuracy metrics.
    - Visualize the results using scatter plots.

## Results

The trained model will predict whether a transaction is fraudulent or not. The performance of the model can be evaluated using accuracy metrics and visualizing the actual vs predicted results.

## License

This project is licensed under the MIT License.
