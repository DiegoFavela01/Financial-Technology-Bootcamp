# Financial-Programming-with-Python
## Challenge 1 University of Berkeley Financial Technology Boot Camp 
The purpose of this Python code is to demonstrate various financial calculations and operations using a set of loans. The code performs different calculations, including finding the quantity, sum, and average cost of loans, calculating the present value of loans, filtering a list of loans, and writing data to a CSV file

### Part 1: Automate the Calculations
In this part, the code starts with a list of loan costs and performs the following calculations:

Finds the quantity of loans and prints it.
Calculates the total sum of the loan and prints it.
Calculates the average cost of loans and prints it.

### Part 2: Analyze Loan Data
In this part, the code uses a dictionary to represent a loan and performs the following calculations:

Gets the future value of the loan and prints it.
Gets the remaining months of the loan and prints it.
Calculates the present value of the loan based on the future value, remaining months, and a discount rate. The present value is then compared to the loan price, and the result of this comparison is printed.

### Part 3: Perform Financial Calculations
In this part, the code defines a function to calculate the present value of a loan based on the future value, remaining months, and annual discount rate. Then, the code uses a dictionary to represent a new loan and performs the following calculations:

Gets the future value and remaining months of the new loan.
Sets the annual discount rate.
Calculates the present value of the new loan using the previously defined function and prints it.

### Part 4: Conditionally filter lists of loans
In this part, the code defines a list of loans in the form of dictionaries and creates an empty list to store the inexpensive loans. The code then iterates over each loan in the list and adds the ones with a loan price less than or equal to $500 to the list of inexpensive loans. Finally, the code prints the list of inexpensive loans.

### Part 5: Save the results
In this part, the code sets the output header and output file path. It then opens a new CSV file in write mode and uses the csv.writer function to write the header and values of the loans in the inexpensive loans list to the CSV file.
