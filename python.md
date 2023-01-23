Q1. How do you load a CSV file into a Pandas DataFrame?
A.)	Import pandas as pd
pd.read_csv(path)

Q2. How do you check the data type of a column in a Pandas DataFrame?
A.)	print(df[“column name”].dtype)

Q3. How do you select rows from a Pandas DataFrame based on a condition?
A.)	Rows from a Pandas dataframe can be selected based on a condition using “Comparison Operators”
Eg: df[df[“column”]>10] – only selects rows which are greater than 10

Q4. How do you rename columns in a Pandas DataFrame?
A.)	df.rename(columns={old_column_name : new_column_name}

Q5. How do you drop columns in a Pandas DataFrame?
A.)	df.drop(columns=[column_names])

Q6. How do you find the unique values in a column of a Pandas DataFrame?
A.)	print(df[column_name].unique())

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
A.)	df['column name'].isna().sum()

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
A.)	df.fillna(value)

Q9. How do you concatenate two Pandas DataFrames?
Q10. How do you merge two Pandas DataFrames on a specific column?
Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
Q12. How do you pivot a Pandas DataFrame?
Q13. How do you change the data type of a column in a Pandas DataFrame?
Q14. How do you sort a Pandas DataFrame by a specific column?
Q15. How do you create a copy of a Pandas DataFrame?
Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?
Q17. How do you calculate the mean of a column in a Pandas DataFrame?
Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
Q20. How do you select specific columns in a DataFrame using their labels?
Q21. How do you select specific rows in a DataFrame using their indexes?
Q22. How do you sort a DataFrame by a specific column?
Q23. How do you create a new column in a DataFrame based on the values of another column?
Q24. How do you remove duplicates from a DataFrame?
Q25. What is the difference between .loc and .iloc in Pandas?

