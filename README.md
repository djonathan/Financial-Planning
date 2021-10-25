# Financial-Planning
Financial planning for emergencies and retirement
---
This project comprises two parts:
* A financial planner for emergencies: Users can assess monthly budget and determine if they have enough reserves for an emergency fund.
* A financial planner for retirement: Starting with their current holdings of cryptocurrencies, stocks, and bonds, users can run Monte Carlo simulations to forecast the portfolio performance after 30 years.
---
## Technologies

Python modules used:

* os
* pandas
* numpy
* alpaca
* matplotlib.pyplot
* local library implementing the Monte Carlo simulation.

---
## In a Jupyter Notebook file:
Initialize data:
* Use the Python Requests library, download current cryptocurrency prices, evaluate crypto holdings with this data.
* Use Alpaca SDK to download current securities data, evaluate stocks and bonds holdings.

Perform analysis:
* Based on cryptocurrency wallet and stocks and bonds portfolio, does user have enough saving for an Emergency Fund?
* Starting with 3 years of closing prices for stock/bond holdings, perform a Monte Carlo simulation of 500 samples for 30 years.

---
## Contributors

[David Jonathan](https://www.linkedin.com/in/david-jonathan-1b9470/)

---

## License

Licensed under the [MIT License](https://github.com/tmbo/questionary/blob/master/LICENSE). Copyright 2021 David Jonathan
