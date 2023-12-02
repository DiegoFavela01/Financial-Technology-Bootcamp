# Financial-Simulation-with-APIs
## Challenge 5 - University of Berkeley Financial Technology Boot Camp
With this code we will create two financial analysis tools using a Jupyter Notebook: a financial planner for emergencies and a financial planner for retirement.

### Part 1: Financial Planner for Emergencies
In this section, we will create a personal financial planner for emergencies. We will assume that each credit union member has a cryptocurrency wallet, stocks, and bonds.

We will complete the following tasks:
- Evaluate the cryptocurrency wallet by using the Requests library
- Evaluate the stock and bond holdings by using the Alpaca SDK
- Evaluate the emergency fund
### Part 2: Financial Planner for Retirement
In this section, we will use the Alpaca API to get historical closing prices for a retirement portfolio. We will then run Monte Carlo simulations to forecast the portfolio performance 30 years from now.

We will complete the following tasks:

- Create the Monte Carlo simulation
- Analyze the retirement portfolio forecasts
- Forecast cumulative returns in 10 years
- Use the MCForecastTools library to create the Monte Carlo simulations for the member's savings portfolio.
- Adjust the weights of the retirement portfolio so that the composition for the Monte Carlo simulation consists of 20% bonds and 80% stocks to find out if the changes will allow members to retire earlier.

## Libraries and Dependencies
This code uses the following libraries:

- Pandas
- Pathlib
- Aplaca Trade Api
- Numpy
- %Matplotlib
####  To install these libraries
```bash
!pip install pandas 
!pip install requests
!pip install alpaca-trade-api 
!pip install python-dotenv 
```
## Files
- The necessary files for this the financial_planning_tools.ipynb file.
- The user will need to create an environment file (.env) to store the values of their Alpaca API key and secret key.
