# Financial-Analysis-with-Pandas
## Challenge 3 - University of Berkeley Financial Technology Boot Camp
This code uses historical trade data for Bitcoin on two exchanges, Bitstamp and Coinbase, to determine if any arbitrage opportunities exist for Bitcoin. The analysis is divided into three phases: collecting the data, preparing the data, and analyzing the data.

### Part 1: Collect the Data
To collect the data needed for analysis, the following steps are taken:

The read_csv function from the Pandas library and the Path module are used to import the data from bitstamp.csv and create a DataFrame called bitstamp. The DatetimeIndex is set as the Timestamp column, and the dates are parsed and formatted.
The head and/or tail function is used to confirm that Pandas properly imported the data.
The same steps are repeated for the coinbase.csv file.

### Part 2: Prepare the Data
To prepare and clean the data for analysis, the following steps are taken:

For the bitstamp DataFrame, all NaN values are replaced or dropped.
The str.replace function is used to remove the dollar signs from the Close column.
The data type of the Close column is converted to float.
Duplicated values are reviewed, and they are dropped if necessary.
The same steps are repeated for the coinbase DataFrame.
### Part 3:  Analyze the Data
The analysis consists of the following tasks:

1. Choosing the columns of data to focus on.
2. Getting the summary statistics and plotting the data.
3. Focusing on specific dates.
4. Calculating the arbitrage profits.

## Libraries and Dependencies
This code uses the following libraries:

- Pandas
- Pathlib
- Numpy
- %Matplotlib
####  To install these libraries
```bash
!pip install pandas
!pip install pathlib
!pip install numpy
```
###  Running the Code
To run the code, open a Jupyter Notebook or JupyterLab session and run each cell of the code sequentially. Make sure that the necessary CSV files (bitstamp.csv and coinbase.csv) are in the same directory as the Jupyter Notebook file.
