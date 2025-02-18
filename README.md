# 🐍 Python Pandas Queries: Data Analysis Project 📊

Welcome to my **Python Pandas Queries** project! In this repository, I utilised the powerful **Pandas library** to perform data analysis on a dataset using various Python queries. The project involves working with common Pandas functions and techniques to clean, transform, and summarise data.

## 🧑‍💻 Project Overview

This project demonstrates how to use the Pandas library in Python to perform various data analysis tasks. I explored different operations, including:

- **Data aggregation** with `groupby()`.
- **Descriptive statistics** using methods like `mean()`, `min()`, `max()`, and `describe()`.
- **Data selection and filtering** using methods such as `loc[]`, `iloc[]`, and logical operators (`&`, `|`).
- **Sorting and counting** using `sort_values()` and `value_counts()`.
- **Data summarisation** with functions like `sum()`, `info()`, `shape()`, `head()`, and `tail()`.

## 🛠️ Tools & Technologies

- **Python**: Programming language used for data analysis.
- **Pandas**: A Python library for data manipulation and analysis.
- **Jupyter Notebook** (optional): Used to execute and document the code.

## 📑 Key Functions Used

Here’s a list of the main functions and methods I used in this project:

- **`value_counts()`**: Counts occurrences of unique values in a column.
- **`sort_values()`**: Sorts data by one or more columns.
- **`ascending`**: Boolean argument used in `sort_values()` to sort in ascending or descending order.
- **`groupby()`**: Groups data based on certain columns for aggregation.
- **`==`**, **`&`**, **`|`**: Logical operators used for filtering data based on conditions.
- **`min()`**, **`max()`**, **`mean()`**: Methods to find minimum, maximum, and average values in a column.
- **`loc[]`**: Used for selecting data by label.
- **`iloc[]`**: Used for selecting data by index position.
- **`describe()`**: Provides a summary of the dataset's descriptive statistics.
- **`sum()`**: Calculates the sum of a series or DataFrame column.
- **`info()`**: Displays information about the DataFrame, including the data types and memory usage.
- **`shape()`**: Returns the number of rows and columns in a DataFrame.
- **`head()`** and **`tail()`**: Displays the first and last few rows of a DataFrame.

## 📊 Project Steps

1. **Data Import**: Imported the dataset using `pd.read_csv()` or other suitable functions.
2. **Exploring the Data**: Used `head()`, `tail()`, and `shape()` to get an overview of the dataset.
3. **Data Cleaning**: Applied filtering and logical operations to clean the data using `&`, `|`, `==`, etc.
4. **Data Aggregation**: Used `groupby()` to group data and aggregate statistics like mean, min, and max values.
5. **Data Analysis**: Utilised `value_counts()`, `sort_values()`, and other functions to derive insights from the data.
6. **Descriptive Statistics**: Applied `describe()` to get a summary of key statistics.


## 🔍 Example Analysis

Here’s an example of a few queries ran in Pandas library.


### Example 1: Using value_counts

<img width="314" alt="Screenshot 2025-02-18 at 22 09 20" src="https://github.com/user-attachments/assets/89a8e15c-00e1-4a8f-945f-27add0c9fb47" />


### Example 2: Using group_by with mean

<img width="374" alt="Screenshot 2025-02-18 at 22 10 24" src="https://github.com/user-attachments/assets/c35eab9d-f98e-4883-9e2e-3af810caf135" />


### Example 3: Using Loc, == , & tools

<img width="590" alt="Screenshot 2025-02-18 at 22 12 05" src="https://github.com/user-attachments/assets/fc81bf4d-415e-4864-b4af-0e18ba56a303" />


### Example 4: Using head()

<img width="380" alt="Screenshot 2025-02-18 at 22 13 32" src="https://github.com/user-attachments/assets/ccd5364d-0ec9-4ce3-969c-a3ed43c96589" />


### Example 5: Using sum to find total null values

<img width="227" alt="Screenshot 2025-02-18 at 22 14 50" src="https://github.com/user-attachments/assets/156a843f-b4db-4357-a901-667943780364" />


## 💡 Key Takeaways

The use of logical operators (&, |, ==) in Pandas allows for flexible and powerful data filtering.
GroupBy is a powerful method for aggregating data and summarising results across categories.
Descriptive statistics provide a quick summary of a dataset, helping to identify trends and outliers.





