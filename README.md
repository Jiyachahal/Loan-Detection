# Loan Detection

This repository contains a project for predicting loan status based on customer data using machine learning models.

## Project Overview

The project involves:
- **Data Cleaning and Preprocessing**: Loading the dataset, handling missing values, and encoding categorical data.
- **Exploratory Data Analysis (EDA)**: Analyzing patterns and relationships using visualization.
- **Feature Engineering**: Identifying key features for better model performance.
- **Model Training and Evaluation**: Training multiple models and evaluating their performance.
- **Model Comparison**: Comparing models to select the most effective one for prediction.

## Dataset

The dataset `loan_detection.csv` includes customer demographic, financial, and past interaction details. It is processed to enable efficient machine learning.

## Results

- Logistic Regression and XGBoost models performed well with over 90% accuracy on the test set.
- Logistic Regression was chosen for its simplicity and efficiency.

### Prerequisites
Ensure you have Python 3.x and the following libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

## How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Jiyachahal/Loan-Detection.git
2. **Open and Run the Jupyter Notebook:**
    [View the Jupyter Notebook](./code.ipynb)

## Insights and Visualizations 
- Data Distribution: Pie charts and bar plots showcase data distribution.
- Feature Correlations: Heatmaps highlight relationships between features and the target variable.
- Model Performance: Metrics like accuracy, precision, recall, and F1-score are reported.

## Contributions 
Contributions and suggestions are welcome. Feel free to fork the repository, make changes, and submit a pull request.
