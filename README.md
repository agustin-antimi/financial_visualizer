# 📊 Financial Visualizer

An interactive financial data visualization tool built with Python. Fetches real-time and historical market data and presents it through dynamic, professional-grade charts via a **Streamlit** web interface.

## Features

- **Real-time market data** powered by yfinance
- **Interactive candlestick charts** with volume overlay
- **S&P 500 ticker lookup** with automatic symbol resolution
- **Customizable date ranges** and time periods
- **Streamlit dashboard** for an intuitive, browser-based experience

## Tech Stack

| Component | Technology |
|-----------|------------|
| Data | yfinance |
| Charts | lightweight-charts |
| Interface | Streamlit |
| Processing | pandas |

## Getting Started

### Prerequisites

- Python 3.10+

### Installation

```bash
git clone https://github.com/your-username/financial_visualizer.git
cd financial_visualizer
pip install -r requirements.txt
```

### Usage

```bash
streamlit run app.py
```

## Project Structure

```
financial_visualizer/
├── src/
│   └── functions.py      # Core data fetching and chart logic
├── tests/                 # Jupyter notebooks for testing
├── requirements.txt
└── README.md
```

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.