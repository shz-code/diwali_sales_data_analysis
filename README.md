# Customer Product Purchase Behavior Analysis

This project analyzes the product purchase behavior of customers based on various factors such as marital status, state, product category, and occupation. The analysis is performed using Diwali sales data.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Introduction

In this project, we aim to gain insights into the product purchase behavior of customers during Diwali sales. By analyzing the provided data, we will explore how factors such as marital status, state, product category, and occupation influence the purchasing decisions of customers.

## Data

The dataset used for this analysis contains information about customer purchases during Diwali sales. It includes the following columns:

- `Marital Status`: The marital status of the customer (e.g., Married, Single).
- `State`: The state in which the customer resides (e.g., Maharashtra, Delhi).
- `Product Category`: The category of the purchased product (e.g., Electronics, Clothing).
- `Occupation`: The occupation of the customer (e.g., Engineer, Doctor).

## Analysis

The analysis in this project involves the following steps:

- Exploratory Data Analysis (EDA): We will perform EDA to gain an understanding of the data, identify any missing values or outliers, and visualize the distributions and relationships between variables.

- Statistical Analysis: We will conduct statistical analyses to uncover patterns and insights related to the purchase behavior based on marital status, state, product category, and occupation. This may involve hypothesis testing, correlation analysis, and other statistical techniques.c

## Results

The results of the analysis will be presented in a clear and concise manner, including visualizations, statistical findings, and insights gained from analysis. The goal is to provide valuable information about the product purchase behavior of customers during Diwali sales and the factors influencing their decisions.

## Run Locally
To run this project locally, follow these steps:

- Clone the repository:
```
git clone https://github.com/shz-code/diwali_sales_data_analysis
```

- Navigate to the project directory:
```
cd diwali_sales_data_analysis
```
### If anaconda is installed:
- Create environment
```
conda env --prefix ./env
```
- Install dependencies
```
conda install jupyter numpy matplotlib seaborn pandas
```
- Activate environment
```
conda activate "your env directory"
```
- Start jupyter notebook
```
jupyter notebook
```
### If anaconda is not installed:
- Install the required dependencies:
```
pip install -r requirements.txt
```
- Run the Jupyter Notebook:

```
jupyter notebook
```

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Main Project](https://github.com/rishabhnmishra/Python_Diwali_Sales_Analysis)