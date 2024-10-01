## ECE 2112 | EXPERIMENT 3 (PYTHON DATA ANALYSIS)
**I. Intended Learning Outcomes:**
1. To identify the codes and functions incorporated in the Pandas library
2. To be able to apply and use the different codes and functions in creating a Python program using a
Pandas library

**II. Instructions:**
Write a Python script/code in the Jupyter Notebook to do the given problems.

**PROBLEM 1:**
Using knowledge obtained from the experiment and demonstrations:
- Load the corresponding .csv file into a data frame named cars using pandas
- Display the first five and last five rows of the resulting cars.
- To solve this problem, I used Pandas to load the CSV file into a DataFrame by executing the command `pd.read_csv('cars.csv')`. This transformed the CSV file into a DataFrame. By applying the `head()` and `tail()` functions, I was able to view the first and last rows of the DataFrame. To specify a different number of rows, you can modify the value inside the parentheses of these functions.

**PROBLEM 2:**
Using the dataframe cars in problem 1, extract the following information using subsetting, slicing and 
indexing operations.
- Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7…) of cars.
-  Display the row that contains the ‘Model’ of ‘Mazda RX4’.
-  How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?
-   Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4 
Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.
- The same DataFrame was utilized to address the problems by applying indexing syntax. By specifying the required indices and columns, and performing the necessary arithmetic operations, the problem was effectively resolved.
