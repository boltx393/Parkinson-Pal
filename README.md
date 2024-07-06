# Heart Attack Risk Predictor with EvalML

## Overview

This project aims to predict the risk of heart attacks using machine learning algorithms. The predictor is built using various algorithms and refined using EvalML to ensure the best performance. 

## Features

- **Multiple Machine Learning Algorithms**: The project utilizes Logistic Regression, Decision Tree, Random Forest, K-nearest neighbors, and Support Vector Machines.
- **Model Evaluation with EvalML**: The performance of the models is refined and evaluated using EvalML.
- **Data Preprocessing**: The data is cleaned and preprocessed to ensure accurate predictions.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/heart-attack-predictor.git
    cd heart-attack-predictor
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
   
2. Open the `Heart_Attack_Risk_Predictor_with_EvalML.ipynb` notebook and execute the cells to train and evaluate the models.

## Project Structure

```
.
├── Heart_Attack_Risk_Predictor_with_EvalML.ipynb  # Main notebook for the project
├── data                                           # Folder containing the dataset
│   └── heart_disease_data.csv                     # Example dataset file
├── requirements.txt                               # List of dependencies
└── README.md                                      # Project README file
```

## Dataset

The dataset used for this project contains various features such as age, gender, blood pressure, cholesterol levels, etc., which are used to predict the likelihood of a heart attack.

## Models Used

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **K-nearest Neighbors**
- **Support Vector Machines**

## Evaluation Metrics

The models are evaluated using various metrics to determine their performance. EvalML is used to refine and improve the models.