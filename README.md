# Principles of Data Analytics - Iris Flower Analysis

**Author**: David Scally
**University**: Atlantic Technological University
**Module**: Principles of Data Analytics
**Class**: January 2025


Reference for layout of Readme - https://medium.com/@kc_clintone/the-ultimate-guide-to-writing-a-great-readme-md-for-your-project-3d49c2023357

## Purpose

This is an anlysis of the famous Iris dataset by the British biologist Ronald Fisher
To complete a set of 10 tasks for the module 'Principles of Data Analytics' - Class of January 2025



See task headings below:

######## to do 26th April Expand with info per each task/ screenshots if needed ########

1.  Source the Data Set
The Iris dataset is loaded using `sklearn.datasets.load_iris()` and converted into a pandas DataFrame. A comparsion between the raw dataset from sklearn vs converted pandas DataFrame

2.  Explore the Data Structure
Initial inspection includes checking data types, size, and a preview of the dataset using `df` and `.info()`.

3.  Summarize the Data
Descriptive statistics (mean,min,max,standard deviation,median) are generated using `.describe()`

4.  Visualize Features
Used `matplotlib` to create histogramsto understand the distribution of each feature.

5.  Investigate Relationships
Created a scatter plot of two features to show relationship between 'petal length (cm)' & 'petal width (cm)'

6.  Analyze Relationship
Use numpy.polyfit to add a regression line to the scatter plot of 'petal length (cm)' & 'petal width (cm)'

7.  Analyze Class Distributions
Create box-plots of the petal lengths for each of the three classes using color-coded plots.

8.  Compute Correlations
Calculate the correlation coefficients between the features & displayed the results as a heatmap using matplotlib.

9.  Fit a Simple Linear Regression
Calculated the coefficient of determination r² & fitted it to a scatter plot

10. Too Many Features
Used seaborn to create a pairplot of the data set & discuss what the pairplot depicts.

## Repositary Contents

 - tasks.ipynb - Jupyter notebook for Data Analyis of Iris Dataset
 - requirements.txt - List of packages used in the analysis
 - README - This file, used to explain the project
 

 ## Installation

1. Clone the repositary

2. Install dependencies



