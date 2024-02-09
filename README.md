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