# Disease Diagnosis – Thyroid Cancer Recurrence Prediction

A Data Science and Machine Learning project that analyzes thyroid cancer patient data and predicts disease recurrence using a Random Forest Classification model.

## Project Overview

This project focuses on analyzing patient data related to thyroid cancer and developing a machine learning model to predict whether the disease has recurred.

The project follows a complete Data Science workflow, including data loading, data cleaning, exploratory data analysis, data visualization, feature preprocessing, model building, and model evaluation.

## Objective

The main objective of this project is to develop a machine learning classification model that predicts thyroid cancer recurrence based on patient and clinical features.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Dataset

The dataset contains demographic and clinical information related to thyroid cancer patients.

The target variable used for prediction is:

- `Recurred` – indicates whether the cancer has recurred (`Yes` or `No`).

The dataset contains features related to:

- Age
- Gender
- Smoking
- Smoking History
- Radiotherapy History
- Thyroid Function
- Physical Examination
- Adenopathy
- Thyroid Cancer Pathology
- Focality
- Risk
- Tumor
- Lymph Nodes
- Cancer Metastasis
- Cancer Stage
- Treatment Response
- Recurrence Status

## Project Workflow

### 1. Data Loading

The thyroid cancer dataset is loaded using Pandas for further analysis and processing.

### 2. Data Exploration

The dataset is explored to understand its structure and identify patterns in the data.

The analysis includes:

- Dataset dimensions
- Data types
- Statistical information
- Duplicate records
- Distribution of categorical variables
- Distribution of numerical variables

### 3. Data Preprocessing

The data is prepared for machine learning by:

- Cleaning and organizing the dataset
- Renaming columns where required
- Grouping relevant categories
- Removing duplicate records
- Converting categorical variables into numerical form
- Preparing features and the target variable
- Applying feature scaling where required

### 4. Exploratory Data Analysis

Various visualizations are created to understand relationships between patient characteristics and cancer recurrence.

The analysis includes:

- Age distribution
- Gender distribution
- Smoking patterns
- Treatment response
- Cancer stage and recurrence
- Risk level and recurrence
- Age groups and recurrence
- Correlation between numerical features

### 5. Model Building

The dataset is divided into training and testing sets using `train_test_split`.

A **Random Forest Classifier** from Scikit-learn is trained to predict thyroid cancer recurrence.

### 6. Model Evaluation

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report

## Model Performance

The Random Forest Classifier achieved **96% accuracy** on the test dataset.

|     Class     | Precision | Recall | F1-Score |
| No Recurrence |   0.96    |  0.98  |   0.97   |
|   Recurrence  |   0.95    |  0.91  |   0.93   |

**Overall Accuracy: 96%**

The test dataset contained **73 samples**.

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature transformation
- Machine learning classification
- Random Forest Classification
- Train-test splitting
- Model evaluation using classification metrics
- Working with healthcare-related datasets

## Project Structure

```text
Disease-Diagnosis-Using-Multiple-Features/
│
├── Disease Diagnosis Project.ipynb
├── Thyroid_Diff.csv
└── README.md

## How to Run the Project

1. Clone or download this repository.
2. Open `Disease Diagnosis Project.ipynb` using Jupyter Notebook or Google Colab.
3. Make sure `Thyroid_Diff.csv` is available in the required location.
4. Run the notebook cells sequentially.
5. View the data analysis, visualizations, model training, and evaluation results.

## Disclaimer

This project is created for educational and learning purposes. It is
not a medical diagnostic system and should not be used to make
real-world medical decisions.

## Author

**Harini K**
