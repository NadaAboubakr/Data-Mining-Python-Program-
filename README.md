# Data Mining for Fire Incident Prediction

This project aims to mine data related to fire incidents and prepare it for predictive modeling. It involves various steps such as handling missing values, removing noise, dealing with duplication, and more. After data mining, the project also includes modeling steps to predict fire incidents using machine learning algorithms.

## Project Overview

The project consists of two main parts: Data Mining and Modeling.

### Data Mining

In the Data Mining phase, the following steps are performed:

1. **Importing Libraries and Loading Data**: Necessary libraries are imported, and the dataset is loaded using pandas' read_csv function.

2. **Handling Missing Values**: Missing values in the dataset are identified and removed using appropriate techniques.

3. **Handling Noise Data**: Outliers are detected and removed from the dataset to ensure data quality.

4. **Dealing with Duplication**: Duplicated rows in the dataset are identified and eliminated.

5. **Handling Irrelevant Features**: Features that do not contribute to the prediction of fire incidents are removed to improve model performance.

6. **Checking Correlation**: Correlation between features is analyzed, and highly correlated features are removed to avoid multicollinearity.

7. **Apply Discretization**: Discrete data is transformed into intervals to reduce data size and complexity.

8. **Final Data View**: The final cleaned dataset is presented to ensure it is ready for modeling.

### Modeling

In the Modeling phase, predictive models are built using the prepared dataset. The following steps are included:

1. **Encoding Categorical Features**: Categorical features are encoded into numerical format to be used in machine learning models.

2. **KNN (K-Nearest Neighbors)**: KNN algorithm is applied with different values of k and distance metrics, and model performance is evaluated.

3. **Decision Tree**: Decision tree classifier is implemented, and model accuracy is assessed using a confusion matrix.

4. **Naïve Bayes**: Gaussian Naïve Bayes algorithm is applied after standardizing numerical features, and classification accuracy is evaluated.

5. **K-Means**: K-Means clustering algorithm is utilized to cluster the data, and final centroids are printed.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib

Usage:
Review the project report for detailed analysis and findings.

Credits:
- The project was completed with contributions from all team members, whose names are mentioned on the first page of the project report.

For any inquiries or further information, please refer to the project report or contact me directly.

