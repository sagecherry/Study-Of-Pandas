# AIM: Study Of Pandas
# OBJECTIVE: Study of Pandas for Data Manipulation and Basic Exploratory Analysis

## THEORY: 
The notebook demonstrates how to create, view, filter, and perform basic statistical operations on structured data using Series and DataFrames.

## Topics Covered

- Importing the Pandas library
- Creating a Pandas Series from a list
- Creating a DataFrame from a dictionary
- Viewing first and last rows (`head()` and `tail()`)
- Basic statistical summary of numeric columns  
  - mean  
  - minimum  
  - maximum
- Filtering rows based on conditions (e.g., marks > 80)

## Key Demonstrations

- Creating and displaying a simple Series
- Building a student marks DataFrame (Name + Marks)
- Showing first 5 and last 5 rows using `head()` and `tail()`
- Calculating average, lowest, and highest marks
- Filtering and displaying students who scored more than 80 marks

## Key Learnings

- `pd.Series()` => 1-dimensional labeled array
- `pd.DataFrame()` => 2-dimensional table-like structure (most common Pandas object)
- `head()` and `tail()` are quick ways to inspect data
- Basic statistics: `.mean()`, `.min()`, `.max()`
- Boolean indexing / filtering: `df[df['column'] > value]`
- Pandas is the foundation for almost all data analysis and machine learning workflows in Python

## Conclusion

This experiment provided a practical introduction to Pandas — one of the most widely used Python libraries for working with tabular data. Mastering Series, DataFrames, basic statistics, and simple filtering is an essential first step toward real-world data analysis and exploratory data analysis (EDA).
