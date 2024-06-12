# Optimization and Predictive Modeling - Supply Chain Management
## Overview

This notebook provides a comprehensive analysis of supply chain data with the objective of optimizing various elements of the supply chain. The analysis covers data pre-processing, visualization, and modeling to gain insights and make data-driven decisions. The notebook includes the following key sections:

1. **Data Pre-Processing**
   - Importing necessary libraries
   - Data cleaning (handling missing and duplicate values)
   - Preparing the data for analysis and modeling

2. **Descriptive Analysis**
   - Overview of the dataset
   - Statistical summary and data types of variables
   - Initial data exploration

3. **Correlation Analysis**
   - Examining relationships between different variables
   - Visualizing correlations using heatmaps and pair plots

4. **Data Visualization**
   - Analyzing key aspects of the data through visualizations
   - Product, customer, route, and transportation mode analysis

5. **Data Modeling**
   - Implementing regression models to predict stock levels and transportation costs
   - Evaluating model performance

## Detailed Description

### 1. Data Pre-Processing

#### 1.1 Importing Libraries
The notebook starts by importing all necessary libraries such as `pandas`, `numpy`, `seaborn`, `matplotlib`, `sklearn`, `statsmodels`, and others to handle data analysis, visualization, and modeling.

#### 1.2 Data Loading and Initial Exploration
The dataset `supply_chain_data.csv` is loaded, and initial exploration is performed to understand the structure and contents of the data.

#### 1.3 Data Cleaning
The dataset is checked for missing and duplicate values, and necessary cleaning steps are taken. Columns are renamed for consistency and ease of use.

### 2. Descriptive Analysis
The descriptive analysis includes checking the shape of the dataset, data types, and providing a statistical summary of the variables. This helps in understanding the basic characteristics of the dataset.

### 3. Correlation Analysis
To understand the relationships between variables, a correlation matrix is generated, and visualized using a heatmap. Categorical variables are encoded into numerical values using `LabelEncoder` before calculating correlations.

### 4. Data Visualization

#### 4.1 Products Analysis
- Total stock levels
- Total order quantities
- Manufacturing costs
- Revenue generated

These aspects are visualized using bar plots and pie charts to understand the distribution and performance of different products.

#### 4.2 Customers Analysis
Customer demographics are analyzed to understand the distribution of products among different customer segments. 

#### 4.3 Customer Segment by Products
The relationship between customer demographics and product types is visualized to identify key customer segments for each product type.

#### 4.4 Routes Analysis
Routes are analyzed in terms of revenue generated, order quantities, transportation costs, and average shipping times.

#### 4.5 Transportation Modes
The performance of different transportation modes is analyzed in terms of revenue, order quantities, transportation costs, and average shipping times.

#### 4.6 Routes and Transportation Modes
The combination of routes and transportation modes is analyzed to understand their impact on supply chain performance.

### 5. Data Modeling

#### 5.1 Regression Models

##### 5.1.1 Linear Regression for Stock Levels
A linear regression model is trained to predict stock levels using relevant features. The model's performance is evaluated using R-squared and visualized through scatter plots.

##### 5.1.2 Linear Regression for Transportation Costs
A linear regression model is trained to predict transportation costs using relevant features. The model's performance is evaluated, and an OLS summary is provided to examine the significance of predictor variables.

## Conclusion
The notebook provides a detailed analysis of supply chain data, enabling insights into various aspects such as product performance, customer behavior, route efficiency, and transportation modes. By building regression models, the notebook helps in predicting key variables like stock levels and transportation costs, aiding in supply chain optimization.

## Dependencies
The notebook requires the following libraries:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `sklearn`
- `statsmodels`
- `plotly`
- `ortools`
- `scipy`

These can be installed using pip if not already available in the environment.

## Usage
To use the notebook:
1. Ensure all dependencies are installed.
2. Load the dataset `supply_chain_data.csv`.
3. Run the cells sequentially to perform data pre-processing, visualization, and modeling.
4. Analyze the output visualizations and model results to derive insights and make data-driven decisions.

This notebook serves as a comprehensive guide for analyzing and optimizing supply chain data, providing valuable insights for improving supply chain performance.
