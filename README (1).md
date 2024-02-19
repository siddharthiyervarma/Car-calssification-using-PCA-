 ## "Vehicle Classification using PCA"




 
Project Overview:
Description:

In this project, the goal is to develop a machine learning model that can accurately predict the Classification of 4 different Vehicles.This project Focuses on understanding how to use PCA to reduce Demionsicnality 

Data Description:

The dataset comprises geometric features extracted from the silhouettes of four "Corgie" model vehicles: a double-decker bus, Chevrolet van, Saab 9000, and Opel Manta 400 cars. This selection aims to facilitate distinguishability among the bus, van, and one of the cars, while creating a challenge in differentiating between the cars.

Domain:

The project resides within the domain of object recognition.

Context:

The primary objective is to categorize a given silhouette into one of three vehicle types, utilizing a set of geometric features extracted from the silhouette. The challenge lies in the varying perspectives from which the vehicle may be observed.

Attribute Information:

All features are numeric and represent geometric characteristics derived from the vehicle silhouettes.
Learning Outcomes:

Exploratory Data Analysis (EDA): Uncover insights and patterns within the dataset to inform subsequent analysis.

Dimensionality Reduction: Implement Principal Component Analysis (PCA) to decrease the number of dimensions in the dataset with minimal information loss.

Model Training using Principle Components: Train a machine learning model using the reduced set of principle components instead of the raw data.

Objective:

The project aims to enhance model efficiency by applying the dimensionality reduction technique - PCA. By training the model on principle components, the objective is to streamline the dataset representation, minimizing redundancy while preserving essential information. This approach aligns with best practices in machine learning, enhancing model interpretability and performance.

## 🛠 Skills Used 
Machine Learning,
Data Cleaning and Processing,
Model Building,
Feature Engineering,
Data Visualization and
Model Evaluation


## Authors

- [@siddharthiyervarma](https://www.github.com/siddharthiyervarma)


## Roadmap
1. Data Preprocessing:

-Data Types (Dtypes):

Checked the types of data in the DataFrame.

Shape (shape):
Explored the dimensions of the dataset to understand the number of rows and columns.

5 Number Summary:
Examined the central tendency and spread of the numerical features using the 5-number summary.

2. Null Values:

Identified and handled missing values, filling them with the median.
Defining Dependent and Independent Variables:

Established the target variable (dependent) and the features (independent) to predict.

3. Visualization:

Histogram of DataFrame (df):

Visualized the distribution of data points in the entire dataset.
Boxplot of Independent Variables:

Examined the spread and potential outliers in each independent variable.
Outliers Handling using IQR:

Employed the Interquartile Range (IQR) to identify and handle outliers.
Independent Variables Correlation (sns heatmap):

Explored the correlation among independent variables using a heatmap.
Pairplot:

Visualized relationships between pairs of variables using a pairplot.

4. Model Building:

Z-Score Standardization:

Standardized the data using the Z-score method.

Confusion Matrix:

Evaluated the model's performance using a confusion matrix.

PCA on 18 Components:

Applied Principal Component Analysis (PCA) to reduce the dimensionality to 18 components.
Eigenvalues and Eigenvectors:

Computed and analyzed the eigenvalues and eigenvectors to understand the variance in the data.

Dimension Reduction:

Using 8 Eigenvalues:

Selected the top 8 eigenvalues for dimension reduction.

Pairplot of Eigenvalues:

Visualized the relationships between the selected eigenvalues.
Linear Model with Original and Reduced Dimensions:

Built a linear model using all 17 independent variables and the 8 new values.
Data Splitting:

Split the dataset into training and testing sets.

5. Model Score Comparison:

Evaluated and compared model performance before and after PCA.

Results:

Model Score on Original Data (18 dimensions): 95.28%
Model Score on Reduced PCA Dimension (8 dimensions): 93.70%
Conclusion:

PCA-driven dimensionality reduction effectively reduced the number of dimensions while maintaining a high level of model accuracy. The reduction from 18 to 8 dimensions resulted in a minor decrease in accuracy but significantly improved computational efficiency