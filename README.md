# Fetching Stock Data with Selenium and Plotting with Pandas and Matplotlib

This project fetches Fortinet, Inc. (FTNT) stock data from Yahoo Finance using Selenium, processes the data using Pandas, and plots the stock prices for the last three months using Matplotlib. The plot is displayed directly in a Jupyter Notebook.

## Prerequisites

Before running the code, please ensure the following:

1. **Python Version**
   - Make sure you are using Python version 3.9.13 or above.
   - You can check your Python version by running:
     ```bash
     python --version
     ```

2. **Install Required Libraries**
   - Install Selenium, Pandas, and Matplotlib using pip:
     ```bash
     pip install selenium pandas matplotlib
     ```

3. **Selenium Version**
   - Ensure that you are using Selenium version 4.21.0 or above.
   - You can check your Selenium version by running:
     ```bash
     pip show selenium
     ```

4. **Download and Setup ChromeDriver**
   - Download the ChromeDriver from [here](https://sites.google.com/chromium.org/driver/downloads).
   - Place the `chromedriver.exe` in the same working directory as your Python script or Jupyter Notebook.

## Notes

- Ensure that `chromedriver` is compatible with your installed version of Google Chrome.
- The script is designed to run in a Jupyter Notebook environment to visualize the plot directly.