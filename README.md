# Employee Attrition Prediction Project

Employee attrition, the phenomenon of employees leaving their jobs, is a significant challenge for organizations. This project utilizes a hypothetical dataset from IBM HR Analytics Employee Attrition & Performance to analyze factors influencing employee attrition and develop a predictive model.

## Problem Statement
The objective of this project is to understand and determine how various factors relate to workforce attrition. By analyzing employee background and characteristics, we aim to predict whether an employee is likely to stay in the company or leave for another job.

## Dataset Overview
- **Size**: The dataset contains 1,470 data points (rows) and 35 features (columns).
- **Features**: Each feature describes an employee's background and characteristics.
- **Label**: The dataset is labeled (supervised learning) with whether the employee is still in the company or has left for another job.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Seaborn and Matplotlib**: For data visualization.
- **Plotly**: For interactive visualizations.
- **Scikit-learn**: For machine learning tasks such as model building, preprocessing, and evaluation.

## Approach
1. **Data Preprocessing**: 
   - Cleaning the data, handling missing values, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzing the relationships between various features and employee attrition.
3. **Feature Engineering**:
   - Selecting relevant features and transforming data if necessary.
4. **Model Building**:
   - Utilizing Gradient Boosting Classifier for predicting employee attrition.
5. **Model Evaluation**:
   - Assessing model performance using metrics such as accuracy, log loss, and confusion matrix.

## Findings
After analyzing the dataset and building the predictive model, it was observed that monthly income and daily rates were identified as the main influencing features causing employee attrition. The developed model achieved an accuracy score of 85%, indicating its effectiveness in predicting employee attrition.

## Conclusion
Understanding the factors contributing to employee attrition is crucial for organizations to implement effective retention strategies. By leveraging machine learning techniques, such as the Gradient Boosting Classifier used in this project, organizations can proactively identify at-risk employees and take necessary actions to improve employee satisfaction and retention.

For detailed implementation and code, refer to the Jupyter notebook provided in this repository.

Feel free to explore further and contribute to the enhancement of the project!
