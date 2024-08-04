
# Heart Disease Predictive Modeling

## Executive Summary
Using Python and various data analysis and visualization libraries, this project performs predictive modeling on the Heart Disease dataset from the UCI Machine Learning Repository. The primary goal is to build a model that can predict the presence of heart disease in patients based on various medical attributes. The analysis includes data loading, preprocessing, exploratory data analysis (EDA), model building, evaluation, and interpretation.

## Business Problem
Heart disease is a leading cause of death worldwide. Early detection and treatment are crucial for improving patient outcomes. This project aims to develop a predictive model to identify individuals at risk of heart disease, allowing for timely medical intervention.

## Methodology
1. **Data Extraction and Cleaning**: Loaded the dataset from the UCI Machine Learning Repository. Inspected the data for missing values and ensured data types were appropriate. Filled missing values with the median of respective columns.
2. **Exploratory Data Analysis (EDA)**: Used descriptive statistics and visualizations to summarize the data and uncover patterns and relationships between features and the target variable.
3. **Data Preprocessing**: Converted the target variable to binary, split the data into training and testing sets, and standardized the features using StandardScaler.
4. **Predictive Modeling**: Built a logistic regression model using the training data to predict heart disease.
5. **Model Evaluation**: Evaluated the model's performance using accuracy, confusion matrix, classification report, ROC curve, and AUC.

## Skills
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Data Visualization**: Histograms, scatter plots, box plots, pair plots, correlation matrices
- **Data Analysis**: Descriptive statistics, data cleaning, data transformation
- **Predictive Modeling**: Logistic regression, model evaluation metrics

## Analysis
1. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of features using histograms and box plots.
   - Examined correlations between features using a heatmap.
   - Identified key features influencing heart disease.

2. **Predictive Modeling**
   - Developed a logistic regression model to predict heart disease presence.
   - Standardized features to ensure model accuracy.
   - Evaluated the model using various metrics to ensure reliability.

## Results & Business Recommendation
### Specific Insights:
- **Key Features**: Age, sex, chest pain type, resting blood pressure, serum cholesterol, maximum heart rate, and exercise-induced angina were significant predictors of heart disease.
- **Model Performance**: Achieved an accuracy of 85%, with an AUC of 0.92, indicating strong model performance.

### Recommendations:
To leverage these insights for clinical use:
1. **Focus on Key Features**: Prioritize these features in medical screenings and diagnostics.
2. **Implement Predictive Model**: Use the model to identify high-risk patients for early intervention.

## Next Steps
1. **Model Optimization**: Experiment with other machine learning models like Decision Trees, Random Forest, or SVM.
2. **Feature Engineering**: Create additional features or ratios based on existing ones to enhance model performance.
3. **Model Deployment**: Develop a deployable version of the model for real-time predictions in a clinical setting.

