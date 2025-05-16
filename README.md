# Goldman Sachs Bank Metrics Dashboard

[![Live Dashboard](https://img.shields.io/badge/Live-Dashboard-blue)](https://goldman-sachs-dashboard-95f562eb9059.herokuapp.com/)

A comprehensive analytics dashboard for comparing Goldman Sachs' financial performance with other major U.S. banks using FDIC quarterly financial data.

## Overview

This dashboard provides financial analysts and stakeholders with an interactive tool to analyze Goldman Sachs' performance metrics compared to peer banks. Built with Python, Dash, and Plotly, it offers a range of visualizations and analytical insights into key banking metrics with a focus on capital ratios, loan portfolios, and performance indicators.

**Live Dashboard**: [https://goldman-sachs-dashboard-95f562eb9059.herokuapp.com/](https://goldman-sachs-dashboard-95f562eb9059.herokuapp.com/)

## Features

- **Side-by-side Bank Comparison**: Compare Goldman Sachs with selected peer banks across multiple metrics
- **Historical Trend Analysis**: View performance trends over customizable time periods (1-20 years)
- **Statistical Insights**: Automatically calculates percentile rankings, volatility, and growth rates
- **Detailed Bank Metrics**: Access comprehensive financial metrics for each bank
- **Correlation Analysis**: Identify banks with similar performance patterns to Goldman Sachs
- **Interactive Data Exploration**: Select metrics, dates, and peer banks through an intuitive interface
- **Responsive Design**: Optimized for both desktop and mobile viewing

## Data Source

The dashboard sources its data directly from the FDIC's public API (Banks Data API at https://banks.data.fdic.gov/api), which provides quarterly financial information for all FDIC-insured institutions. Key metrics include:

- Asset and deposit information
- Loan portfolio composition
- Capital ratios
- Risk-based metrics
- Efficiency and performance indicators

## Key Metrics Tracked

- Real Estate and Commercial Loan Exposure
- Capital Adequacy Ratios
- Return on Assets and Equity
- Loan Performance Metrics
- Nonperforming Asset Ratios
- Net Interest Margin
- Efficiency Ratio

## Technology Stack

- **Python**: Core application logic and data processing
- **Dash & Plotly**: Interactive visualization framework
- **Pandas & NumPy**: Data manipulation and analysis
- **SciPy**: Statistical calculations
- **FDIC API**: Data source integration
- **Heroku**: Application hosting

## Local Development Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/goldman-sachs-dashboard.git
   cd goldman-sachs-dashboard
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

5. Navigate to `http://127.0.0.1:8050/` in your browser

## Implementation Notes

- Implements an intelligent caching system to reduce API calls
- Includes fallback data generation for testing and development
- Offers responsive visualizations that adapt to different screen sizes
- Features a color scheme based on Goldman Sachs' brand guidelines

## License

MIT License

## Disclaimer

This dashboard is for informational purposes only and does not constitute financial advice. All financial data is sourced from publicly available FDIC reports.
