# Principles of Data Analytics - Iris Flower Analysis

**Author**: David Scally  
**University**: Atlantic Technological University  
**Module**: Principles of Data Analytics  
**Class**: January 2025  


## Purpose

This is an analysis of the famous Iris dataset by the British biologist Ronald Fisher. The Iris dataset is a great entry-level dataset that allows us to explore relationships between features of iris flowers and practice fundamental data analysis techniques.
This will be accomplished by completing a set of 10 tasks for the module 'Principles of Data Analytics' - Class of January 2025


## Stated Aim  

Complete 10 tasks outlined in course module exploring, visualising & analysing the dataset.

See 10 task headings below:


1.  **Source the Data Set**
The Iris dataset is loaded using `sklearn.datasets.load_iris()` and converted into a pandas DataFrame. A comparison between the raw dataset from sklearn vs converted pandas DataFrame

2.  **Explore the Data Structure**
Initial inspection includes checking data types, size, and a preview of the dataset using `df` and `.info()`.

3.  **Summarize the Data**
Descriptive statistics (mean,min,max,standard deviation,median) are generated using `.describe()`

4.  **Visualise Features**
Used `matplotlib` to create histograms to understand the distribution of each feature.

5.  **Investigate Relationships**
Created a scatter plot of two features to show relationship between 'petal length (cm)' & 'petal width (cm)'

6.  **Analyze Relationship**
Use numpy.polyfit to add a regression line to the scatter plot of 'petal length (cm)' & 'petal width (cm)'

7.  **Analyze Class Distributions**
Create box-plots of the petal lengths for each of the three classes using color-coded plots.

8.  **Compute Correlations**
Calculate the correlation coefficients between the features & displayed the results as a heatmap using matplotlib.

9.  **Fit a Simple Linear Regression**
Calculated the coefficient of determination r² & fitted it to a scatter plot

10. **Too Many Features**
Used seaborn to create a pairplot of the data set & discuss what the pairplot depicts.

## Repository Contents

 - tasks.ipynb - Jupyter notebook for Data Analysis of Iris Dataset
 - requirements.txt - List of packages used in the analysis
 - README - This file, used to explain the project
 

 ## Installation

1. Clone the repository

git clone https://github.com/Mr-Scarf/principles_of_data_analytics.git

2. Install dependencies - see file 'requirements.txt'

pip install -r requirements.txt

3. Open file `tasks.ipynb` Jupyter notebook  and run the tasks.



## References

- [GeeksforGeeks: Iris Dataset Overview](https://www.geeksforgeeks.org/iris-dataset/)
- [Curran's Gist: Iris Dataset Visualization](https://gist.github.com/curran/a08a1080b88344b0c8a7)

