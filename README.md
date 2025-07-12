# Historical Stock Analysis Dashboard

## Description
This project explores historical stock data of **Tesla (TSLA)** and **GameStop (GME)** using Python.  
It demonstrates the use of:
- `yfinance` for stock data extraction,
- `BeautifulSoup` for web scraping financial data,
- `Plotly` for building interactive visual dashboards.

The analysis is structured around 6 questions, from data acquisition to visualization.

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/cristinaverse/stock-analysis-dashboard.git
cd stock-analysis-dashboard
pip install -r requirements.txt
```

---

## Usage

Run the main analysis script:

```bash
python stock_analysis_main.py
```

> Or open it in **Jupyter Notebook** or **Google Colab** to interactively run and visualize outputs.

---

## Project Structure

```
stock-analysis-dashboard/
├── README.md
├── requirements.txt
├── stock_analysis_main.py
├── notebooks/
│   ├── question1_tesla_data.ipynb
│   ├── question2_tesla_revenue.ipynb
│   ├── question3_gme_data.ipynb
│   ├── question4_gme_revenue.ipynb
│   ├── question5_tesla_plot.ipynb
│   └── question6_gme_plot.ipynb
└── screenshots/
    ├── question1_tesla_data.png
    ├── question2_tesla_revenue.png
    ├── question3_gme_data.png
    ├── question4_gme_revenue.png
    ├── question5_tesla_dashboard.png
    └── question6_gme_dashboard.png

```

---

## Questions Covered

1. Extract Tesla stock data using `yfinance`
2. Scrape Tesla revenue data from Macrotrends
3. Extract GameStop stock data using `yfinance`
4. Scrape GameStop revenue data from Macrotrends
5. Plot interactive Tesla stock + revenue dashboard
6. Plot interactive GameStop stock + revenue dashboard

---

## Author

Made with ❤️ by [Cristina](https://github.com/cristinaverse)

---

## GitHub Repository
https://github.com/cristinaverse/stock-analysis-dashboard
