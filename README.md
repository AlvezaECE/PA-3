# PA 3 - Python Data Analysis (PANDAS)

## I. Intended Learning Outcomes: 
1. To identify the codes and functions incorporated in the Pandas library
2. To be able to apply and use the different codes and functions in creating a Python program using a
Pandas library

## II. Instructions:
Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter
notebook in the dedicated submission bin.

For this programming assignment, download the following file and save to your default user folder: https://bit.ly/Cars_file

## Problem 1: Alveza_Pandas-P1.ipynb
Using knowledge obtained from the experiment and demonstrations: 
1. Load the corresponding .csv file into a data frame named cars using pandas
2. Display the first five and last five rows of the resulting cars.

### Documentation for Problem 1:
1. I used panda's function **read_csv()** to load the CSV files provided into the dataframe.
2. I also used panda's functions **.head()** and **.tail()** which, by default, shows the first and last 5 rows of the dataframe.

## Problem 2: Alveza_Pandas-P2.ipynb
Using the dataframe cars in problem 1, extract the following information using subsetting, slicing and
indexing operations.
1. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7...) of cars.
2. Display the row that contains the ‘Model’ of ‘Mazda RX4’.
3. How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?
4. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4
Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.

### Documentation for Problem 2:
1.  To formulate Part A, I used **iloc[:5, 0::2]**, wherein **::2** would select every second column **(1, 3, 5, 7,...)**.
2.  In Part D, I used **.isin(specific_models)** which filters the dataframe to only include the specified models.

# Author
John Migz D. Alveza
## Date of Submission
September 17, 2024
## Section
2ECE-C
