Equal Weights Portfolio

A Python-based financial analysis project that explores an equal-weighted investment portfolio consisting of the top 50 Indian stocks.

Overview

An Equal-Weight Portfolio is an investment strategy in which every stock in the portfolio receives the same allocation, regardless of its market capitalization.

Unlike market-cap-weighted portfolios, where larger companies dominate the allocation, an equal-weighted portfolio distributes capital uniformly across all selected stocks.

This project uses Python to work with a dataset of the top 50 Indian stocks and construct an equal-weighted portfolio.

Project Objectives

* Understand the concept of equal-weighted portfolio allocation.
* Analyze a selection of 50 leading Indian stocks.
* Calculate equal capital allocation for each stock.
* Explore portfolio construction using Python and financial data.

Methodology

For a portfolio containing N stocks, the allocation to each stock is:

[
Weight = \frac{1}{N}
]

For 50 stocks:

[
Weight = \frac{1}{50} = 0.02 = 2%
]

Therefore, each stock receives an equal allocation of 2% of the total portfolio.

For example, with an initial investment of ₹1,00,000:

* Number of stocks: 50
* Allocation per stock: 2%
* Investment per stock: ₹2,000

Tech Stack

* Python
* Jupyter Notebook
* Pandas
* NumPy

Project Structure

Equal_Weights/
│
├── equalWeights.ipynb
├── top_50_indian_stocks.csv
└── README.md

Getting Started

1. Clone the repository

git clone https://github.com/ankurgithb/Equal_Weights.git

2. Navigate to the project directory

cd Equal_Weights

3. Install dependencies

pip install pandas numpy jupyter

4. Run the notebook

jupyter notebook equalWeights.ipynb

Equal Weight vs Market Capitalization Weight

Feature	Equal Weighted	Market Cap Weighted
Allocation	Equal across all stocks	Based on market capitalization
Large Companies	Same weight as smaller companies	Higher weight
Diversification	More uniform allocation	Concentrated in larger companies
Rebalancing	Usually requires periodic rebalancing	Weights change with market capitalization

Future Improvements

* Integrate live stock market data.
* Calculate historical portfolio returns.
* Compare equal-weighted and market-cap-weighted portfolios.
* Implement portfolio rebalancing.
* Calculate risk metrics such as volatility and Sharpe ratio.
* Visualize portfolio performance over time.

Disclaimer

This project is for educational and research purposes only. It does not constitute financial or investment advice.
