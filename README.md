# data-fun-eda

### Dataset Description
This Python Exploratory Data Analysis project will analyze the "Dow Jones" dataset from the Seaborn library. It contains the price of the Dow Jones from 1914-12-01 to 1968-12-01. The dataset can be accessed via Github: https://github.com/mwaskom/seaborn-data/blob/master/dowjones.csv 

### Environment Setup and How to Install and Run the Project

1. Create and clone repository to VSCode
- Create a new GitHub repository named datafun-06-eda.
- Clone the repository to your local machine.

2. Create and Activate Virtual Environment
- Create a Project Virtual Environment in the .venv folder.
- Activate the Project Virtual Environment.
```console
py -m venv .venv
.\.venv\Scripts\Activate
```

3. Requirements
- Install packages 
```console
py -m pip install jupyterlab pandas matplotlib seaborn pyarrow
```
- Freeze your requirements to requirements.txt. 
```console
py -m pip install requests
py -m pip freeze > requirements.txt
```

4. Git Ignore
- Add a useful .gitignore to the root project folder.


## Table of Contents

1. [Summary](#summary)
2. [Dependencies](#dependencies)
3. [Usage](#usage)
4. [Data Acquisition](#data-acquisition)
5. [Initial Data Inspection](#initial-data-inspection)
6. [Initial Descriptive Statistics](#initial-descriptive-statistics)
7. [Data Exploration](#data-exploration)
    - Histograms
    - Dow Jones Performance Status Count
    - Line Chart of Selling Price
    - Bar Chart of Selling Price
    - Histogram of Selling Price
    - Bar Chart of Price Change
8. [Conclusion](#conclusion)

## Summary

The project analyzes the Dow Jones dataset to gain insights into its historical performance. It employs exploratory data analysis techniques to understand trends, patterns, and fluctuations in the DJIA over the specified period. The goal is to assess the long-term viability of investing in the DJIA.

## Dependencies

The project requires the following Python libraries:
- pandas
- matplotlib
- seaborn

## Usage

To run the project, ensure you have Python installed along with the required dependencies. Then, execute the Python script `nolan_eda.ipynd`. Make sure to have the Dow Jones dataset (`dowjones`) accessible in your working directory or adjust the data acquisition step accordingly.

## Data Acquisition

The project loads the Dow Jones dataset using seaborn's `load_dataset` function. It provides a brief overview of the dataset by displaying the first few rows.

## Initial Data Inspection

The initial data inspection step involves examining the structure of the dataset, including its shape and data types, to gain a better understanding of the available information.

## Initial Descriptive Statistics

Descriptive statistics are calculated to summarize the numerical aspects of the dataset. These statistics provide insights into central tendencies and variability of the data.

## Data Exploration

Various exploratory data analysis techniques are employed to explore different aspects of the Dow Jones dataset, including:

- Histograms: to visualize the distribution of price changes and selling prices.
- Dow Jones Performance Status Count: to analyze the frequency of different performance statuses.
- Line Chart of Selling Price: to observe the trend of selling prices over time.
- Bar Chart of Selling Price: to compare selling prices across different dates.
- Histogram of Selling Price: to further examine the distribution of selling prices.
- Bar Chart of Price Change: to visualize the price changes over time.

## Conclusion

The examination indicatee that over time, the Dow Jones Industrial Average (DJIA) has displayed a consistent upward trajectory, notwithstanding intermittent bouts of instability. Individuals with a focus on long-range investment objectives might deem the DJIA viable.
