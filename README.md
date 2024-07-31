# Value at Risk Portfolio

This repository contains a Python script for calculating and visualizing a stock portfolio's Value at Risk (VaR) using three different methods: Variance-Covariance, Historical Simulation, and Monte Carlo Simulation.

## Features

- **Fetch Historical Stock Data**: Retrieve historical stock data for multiple tickers using the `yfinance` library.
- **Calculate VaR**:
  - **Variance-Covariance Method**: An analytical approach is based on returns' mean and standard deviation.
  - **Historical Simulation Method**: Non-parametric approach based on historical returns.
  - **Monte Carlo Simulation Method**: Simulation-based approach using randomly generated returns.
- **Visualize Return Distributions**: Plot the distribution of returns and indicate the VaR threshold.

## Requirements

- Python 3.x
- pandas
- numpy
- yfinance
- scipy
- matplotlib

Install the required libraries using:
```bash
pip install pandas numpy yfinance scipy matplotlib
```
## Usage
Clone the repository:

```bash
git clone https://github.com/ejb1987/Portfolio_VaR.git
cd Portfolio_VaR
```
Run the script:

```bash
python VaR.ipynb
```
Follow the prompts to enter your portfolio details:

### Example
Here's a brief example of how to run the script and what to expect:
```
Enter the stock tickers (comma-separated): AAPL, MSFT, META
Enter the initial investment amounts (comma-separated): 1000, 2000, 250
Enter the number of days: 10
Enter the confidence level (e.g., 0.95 for 95%): .95

[*********************100%%**********************]  3 of 3 completed

Portfolio Value at Risk (VaR) using the Variance-Covariance method at 95.00% confidence level is:
9.05%
$294.05


Portfolio Historical Value at Risk (VaR) at 95.00% confidence level is:
7.55%
$245.40


Portfolio Monte Carlo Value at Risk (VaR) at 95.00% confidence level is:
7.44%
$241.66

```
## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Contact
For any questions or issues, please open an issue in this repository or contact ehsan.j.b.66@gmail.com.
