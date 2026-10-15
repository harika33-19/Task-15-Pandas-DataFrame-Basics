# Task-15-Pandas-DataFrame-Basics

## Task Overview
Learn how to create Pandas DataFrames from dictionaries and datasets, and explore rows, columns, shape, data types, and summary information.
## Objective
Understand the primary Pandas structure used for tabular data analysis.
## Tools Used
- Python
- Pandas
- Jupyter Notebook / Google Colab
## Tasks Completed
- Create a DataFrame manually using pd.DataFrame()
- Load a real dataset into a DataFrame
- Display the first few rows using head()
- Inspect rows and columns, shape, and data types
- Review dataset information using info()
- Generate numerical summary statistics using describe()
## Example Code
import pandas as pd

# Create a DataFrame from a dictionary
data = {
    "Name": ["Anu", "Ravi", "Sneha"],
    "Age": [20, 21, 19],
    "Marks": [85, 90, 88]
}

df = pd.DataFrame(data)
print(df)

# Inspect the DataFrame
print(df.head())
print("Shape:", df.shape)
print("Columns:", df.columns)
print(df.dtypes)
df.info()
print(df.describe())
## Dataset Suggestions
- Titanic dataset
- Iris dataset
Use a CSV file you have downloaded or a dataset URL that is available to you. If loading a local CSV, make sure the file is uploaded to Colab or placed in the correct working directory.
## Key Learnings
- A DataFrame stores tabular data in rows and columns.
- head() previews the first rows.
- shape returns the number of rows and columns.
- columns lists the column names.
- dtypes shows the data type of each column.
- info() summarizes column types and non-null counts.
- describe() provides summary statistics for numerical columns by default.
Conclusion
This task builds a foundation for exploring, inspecting, and summarizing datasets with Pandas.
