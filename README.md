# Z-Score Statistics of Stocks

## Overview

This project involves building a model to generate Z-Score statistics for five stocks from different Global Industry Classification Standard (GICS) sectors over a period of six months. The project utilizes various Python libraries for data analysis and visualization.

## Features

- **Data Download**: Uses `yfinance` to download historical stock prices.
- **Data Analysis**: Utilizes `Numpy` and `Pandas` for efficient data manipulation and calculation of Z-Scores.
- **Data Visualization**: Employs `Matplotlib` to create visual representations of the stock data and Z-Scores.

## Importance

- **Risk Assessment**: Z-Scores help in identifying how far a stock's price is from its mean in terms of standard deviations, providing insight into its volatility and risk.
- **Comparative Analysis**: By analyzing stocks from different GICS sectors, investors can compare their performance and volatility, aiding in diversification strategies.
- **Informed Decision-Making**: The visualizations generated in this project make it easier for investors to interpret the data and make informed investment decisions.

## Project Structure

- **data_download.py**: Script to download stock prices using `yfinance`.
- **data_analysis.py**: Script to calculate Z-Scores using `Numpy` and `Pandas`.
- **data_visualization.py**: Script to plot stock prices and Z-Scores using `Matplotlib`.
- **README.md**: Project documentation.

## Dependencies
- **yfinance**
- **Numpy**
- **Pandas**
- **Matplotlib**
