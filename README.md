# Smartwatch Health Alert Prediction

## Project Overview
This project focuses on predicting health alert types using smartwatch-generated health data. The workflow includes data preprocessing, exploratory data analysis (EDA), machine learning model training, evaluation, and dimensionality reduction using Principal Component Analysis (PCA).

## Objectives
- Analyze smartwatch health data.
- Identify patterns and relationships between health metrics.
- Build predictive models for health alert classification.
- Compare the performance of multiple machine learning algorithms.
- Apply PCA to reduce dimensionality while retaining important information.

## Dataset
The dataset contains smartwatch health-related attributes and corresponding health alert types. It is used to train and evaluate machine learning models for classification.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Data Preprocessing
- Handling missing values
- Removing duplicate records
- Label Encoding
- Feature Scaling using StandardScaler
- Train-Test Split

## Exploratory Data Analysis
- Count Plot Visualization
- Correlation Heatmap
- Feature Relationship Analysis

## Machine Learning Models
The following classification algorithms were implemented and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Model Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

## Principal Component Analysis (PCA)
PCA was applied to reduce the dimensionality of the dataset and transform the features into principal components while preserving most of the variance.

## Results
The models were trained and compared based on their performance metrics. PCA was used to simplify the feature space and support further analysis.

## Repository Structure

```
Smartwatch-Health-Alert-Prediction/
│
├── Smartwatch_Health_Alert_Prediction.ipynb
├── smartwatch_health_alerts_dataset.csv
├── countplot.png
├── heatmap.png
└── README.md
```

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Feature selection techniques
- Deployment as a web application
- Real-time smartwatch data integration

## Author
Rithika Senthil

