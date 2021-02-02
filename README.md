# Financial Planner API

![](Images/API.png)

As a FinTech professional, you’ve now decided to start a FinTech consulting firm that focuses on projects to benefit local communities. You've just landed your first contract, in which you'll be working with a large credit union and building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things:

First: They should be able to assess their monthly budget. 

Second:They should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. 

The Chief Technology Officer (CTO) of the credit union wants you to develop a prototype application to present at its next assembly!


---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/) - For data cleaning, preparation and manipulation


Below is a breakdown of API's:

* [API's](https://medium.com/@perrysetgo/what-exactly-is-an-api-69f36968a41f/) - Application Programming Interface: Software intermediary that allows two applications to talk to each other

---

## Installation Guide

Create a new file and name it .env
	
Sign-up for a free `alpaca` account
	- Copy your API Keys from the Alpaca Dashboard and add it to your .env file using:
    
	ALPACA_API_KEY = "YOUR_API_KEY_HERE"
	ALPACA_SECRET_KEY = "YOUR_SECRET_KEY_HERE"

---

## Usage


You’ll use a Jupyter Notebook to create two financial analysis tools in order to present the following information at the next assembly, as requested by the Chief Technology Officer of the credit union!

A financial planner for emergencies: The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

A financial planner for retirement: This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations. The simulation should reflect the picture below, which will help you create analyze the information. 

![](Images/5-4-monte-carlo-line-plot.png)

---

## Contributors

Brought to you by Edgar Coronado

---

## License

MIT