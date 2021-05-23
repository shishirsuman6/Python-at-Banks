# python-homework
Unit 2 | Homework Assignment: Automate Your Day Job with Python

1. Create a new GitHub repo called `python-homework`. Then, clone it to your computer.

2. In your local git repository, create a directory for both of the Python activities. Use folder names that correspond to the activities: **PyBank** and **PyRamen**.

3. In each folder you just created, add a new file called `main.ipynb`. Remember that to create this file you will need to use JupyterLab to correctly generate the .ipynb file format. This will be the main notebook to run for each analysis.

4. Push the above changes to GitHub.

## Project Details

### 1) [PyBank](PyBank/)
```
Create a Python script for analyzing the financial records of a company.

financial dataset is in this file: budget_data.csv
filepath: "../PyBank/Resources/budget_data.csv"
This dataset is composed of two columns, Date and Profit/Losses

Create a Python script that analyzes the records to calculate each of the following:
1) The total number of months included in the dataset.
2) The net total amount of Profit/Losses over the entire period.
3) The average of the changes in Profit/Losses over the entire period.
4) The greatest increase in profits (date and amount) over the entire period.
5) The greatest decrease in losses (date and amount) over the entire period.


Resulting analysis should look similar to the following:

Financial Analysis
----------------------------
Total Months: 86
Total: $38382578
Average  Change: $-2315.12
Greatest Increase in Profits: Feb-2012 ($1926159)
Greatest Decrease in Profits: Sep-2013 ($-2196167)

Final script should print the analysis to the terminal and export a text file with the results.

Output text file location: "../python_homework/PyBank/output.txt"

```

### 2) [PyRamen](PyRamen/)

```
Create a python script to analyze your business's financial performance by cross-referencing your 
sales data with your internal menu data to figure out revenues and costs for the year.

Read the Data:
--------------

Menu dataset is in this file: menu_data.csv
filepath: "../PyRamen/Resources/menu_data.csv"
This dataset is composed of columns: item,category,description,price,cost

Sales dataset is in this file: sales_data.csv
filepath: "../PyRamen/Resources/sales_data.csv"
This dataset is composed of columns: Line_Item_ID, Date, Credit_Card_Number, Quantity, Menu_Item


Manipulate the Data:
--------------------

Create a report dictionary to hold the future aggregated per-product results
01-count: the total quantity for each ramen type
02-revenue: the total revenue for each ramen type
03-cogs: the total cost of goods sold for each ramen type
04-profit: the total profit for each ramen type

Write out the contents of the report dictionary to a text file. 
The report should output each ramen type as 
the keys and 01-count, 02-revenue, 03-cogs, and 04-profit metrics as the values for every ramen type.

Output text file location: "../python_homework/PyRamen/output.txt"

```