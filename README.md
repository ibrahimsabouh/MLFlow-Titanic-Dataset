# MLflow Titanic Project

This project demonstrates how to use **MLflow** for tracking experiments and managing machine learning models. The dataset used is the Titanic dataset, which involves predicting the survival of passengers based on various features.

## Project Overview

* **Objective**: To build and evaluate multiple machine learning models for the Titanic dataset and track experiments using MLflow.
* **Features**:
  * Experiment tracking with MLflow
  * Model performance comparison using different scalers and classifiers
  * Model registration and lifecycle management with the MLflow Model Registry
  * Use of input signatures and examples for better reproducibility

## Dataset

The dataset used in this project is the Titanic dataset, which is included as `train.csv`. The dataset contains the following key features:

* `Pclass`: Passenger class
* `Age`: Age of the passenger
* `SibSp`: Number of siblings/spouses aboard
* `Parch`: Number of parents/children aboard
* `Fare`: Ticket fare
* `Sex`: Gender of the passenger
* `Embarked`: Port of embarkation
* `Survived`: Target variable indicating survival (1 for survived, 0 for not survived)

## Project Structure

```
MLflow_Project/
├── train.csv           # Dataset file
├── MLFlow.ipynb       # Jupyter Notebook with MLflow implementation
├── requirements.txt   # Python dependencies
├── .gitignore        # Ignored files and folders
└── README.md         # Project documentation (this file)
```

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/MLflow_Titanic_Project.git
   cd MLflow_Titanic_Project
   ```

2. **Set up the environment**:
   * Install Python (version >= 3.7)
   * Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run MLflow Tracking Server** (Optional):
   * To access the MLflow UI, run the following command:
     ```bash
     mlflow ui
     ```
   * Open `http://127.0.0.1:5000` in your browser

4. **Run the Jupyter Notebook**:
   * Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   * Open `MLFlow.ipynb` and follow the steps to execute the code

## How It Works

1. **Data Preprocessing**:
   * Handles missing values and categorical variables
   * Applies different scalers (`StandardScaler`, `MinMaxScaler`, `RobustScaler`)

2. **Model Training**:
   * Trains classifiers like `Decision Tree`, `Random Forest`, and `Gradient Boosting`

3. **Experiment Tracking**:
   * Logs parameters, metrics, and artifacts (e.g., classification reports) using MLflow

4. **Model Registry**:
   * Registers models for lifecycle management (Staging, Production)

5. **Evaluation**:
   * Compares models based on accuracy and detailed classification reports

## Results

* The project tracks multiple models and scalers, comparing their accuracy
* The MLflow Model Registry is used to manage the best-performing models

## Contact

For any questions or feedback, please contact:

**Ibrahim Sabouh**
* LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/ibrahim-sabouh-5782b4255/)
* GitHub: [Your GitHub Profile](https://github.com/ibrahimsabouh)
