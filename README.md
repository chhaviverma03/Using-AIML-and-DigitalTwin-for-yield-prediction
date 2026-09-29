
# Yield Prediction Using AI/ML and Digital Twin Technology

## Overview

This project focuses on predicting agricultural crop production using Machine Learning and exploring the application of Digital Twin technology in smart agriculture.

The system uses soil characteristics, climatic conditions, and agricultural data to train regression models that estimate crop production. Multiple ML algorithms are evaluated to analyze their prediction performance.

The project aims to support data-driven agricultural planning and provide a foundation for future Digital Twin-based crop simulation.

## Objectives

- Predict agricultural crop production using machine learning.
- Analyze the relationship between soil, climatic, and agricultural parameters.
- Train and evaluate multiple regression algorithms.
- Compare model performance using standard evaluation metrics.
- Explore the integration of AI/ML with Digital Twin technology for smart agriculture.

## Technologies Used

| Category | Tools and Libraries |
|---|---|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| ML Algorithms | Gradient Boosting, Decision Tree, KNN, Ridge Regression, LightGBM |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook / Google Colab |

## Project Structure

```text
Yield-Prediction-AIML-and-Digital-Twin-Technology/
│
├── Yield prediction/
│   ├── dataset/
│   │   ├── Crop_production.csv
│   │   └── Crop_recommendation.csv
│   │
│   └── Yield_Prediction.ipynb
│
├── README.md
└── .gitignore
```

*Note: The notebook and dataset filenames above are illustrative. Update them to match the actual filenames in your repository.*

## Dataset

The project uses agricultural datasets containing crop production information and crop-related parameters.

The features used in the prediction pipeline include:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Soil pH
- Rainfall
- Temperature
- Cultivated area
- Historical crop production / yield information

The datasets are used for data exploration, preprocessing, model training, and evaluation.

## Methodology

### 1. Data Preprocessing

- Load agricultural datasets using Pandas.
- Inspect the data and handle missing values where required.
- Perform exploratory data analysis.
- Prepare input features and target variables.
- Split the dataset into training and testing sets.

### 2. Model Development

Multiple regression algorithms are explored for crop production prediction:

| Algorithm | Description |
|---|---|
| Gradient Boosting Regressor | Ensemble learning using sequential decision trees |
| Decision Tree Regressor | Tree-based regression model |
| K-Nearest Neighbors (KNN) | Regression based on neighboring data points |
| Ridge Regression | Linear regression with L2 regularization |
| LightGBM | Gradient boosting framework based on decision trees |

### 3. Model Evaluation

The models are evaluated using the following metrics:

**R² Score**

Measures how well the model explains the variance in the target variable.

**Mean Absolute Error (MAE)**

Measures the average absolute difference between actual and predicted values.

**Mean Squared Error (MSE)**

Measures the average squared prediction error.

These metrics are used to compare model performance on the test dataset.

## Digital Twin Concept

A Digital Twin is a virtual representation of a physical system that can be used to monitor, simulate, and analyze its behavior.

In the context of this project, the concept involves representing an agricultural farm using soil, weather, and crop-related data.

A potential Digital Twin workflow is:

1. Collect soil and environmental data from agricultural fields.
2. Represent farm conditions in a virtual model.
3. Use machine learning models to estimate crop production.
4. Explore how changes in environmental and agricultural parameters affect predicted yield.

The current implementation primarily focuses on machine learning-based prediction. Real-time sensor integration, dynamic farm simulation, and a complete Digital Twin system are potential future extensions.

## Future Scope

- Develop a Digital Twin simulation using MATLAB/Simulink.
- Integrate real-time agricultural sensor data.
- Develop an interactive dashboard for crop production prediction.
- Explore hybrid physics-based and machine learning models.
- Extend the system to support scenario-based agricultural analysis.

## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Navigate to the Project Directory

```bash
cd YOUR_REPOSITORY
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter lightgbm
```

Install any additional libraries required by the notebook.

### 4. Run the Notebook

```bash
jupyter notebook
```

Open the crop yield prediction notebook and execute the cells sequentially.

## Applications

- Agricultural production forecasting
- Data-driven crop planning
- Analysis of soil and climatic factors
- Smart agriculture research
- AI/ML applications in agricultural systems

## Author

**Chhavi Verma**

B.Tech – Electronics Engineering  
Rajiv Gandhi Institute of Petroleum Technology (RGIPT)
