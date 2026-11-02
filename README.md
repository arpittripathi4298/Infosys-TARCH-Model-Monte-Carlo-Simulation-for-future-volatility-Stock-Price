<div align="center">

# 📈 Infosys Volatility & Price Simulation 
**Advanced TARCH Modeling & Monte Carlo Forecasting**

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&logo=Jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/)

*Unlocking financial market patterns through asymmetric volatility clustering and stochastic price path simulations.*

---

</div>

## 🌟 About The Project

Financial markets react differently to positive and negative shocks. This project dives deep into the historical performance of **Infosys (INFY.NS)**, utilizing advanced econometric techniques to model this asymmetry. By leveraging a Threshold ARCH (TARCH / GJR-GARCH) model, we accurately estimate conditional volatility and power a robust Monte Carlo simulation to project future price distributions.

All analysis, modeling, and visualization are contained within a single, highly documented notebook: **"TARCH Model for Infosys.ipynb"**.

### ✨ Key Highlights
* **Automated Data Pipeline:** Directly fetches 10 years of market data using `yfinance`.
* **Asymmetric Volatility Modeling:** Captures the "leverage effect" (where bad news drives volatility higher than good news of the same magnitude).
* **Monte Carlo Engine:** Simulates 10,000 unique forward-looking variance paths.
* **Geometric Brownian Motion:** Projects 30-day future stock price trajectories with drift adjustment.
* **Dark-Mode Analytics Dashboard:** Generates a stunning 3-panel Matplotlib/Seaborn visualization.

---

## 🧰 Tech Stack

This project is built using the foundational tools of Python's data science and quantitative finance ecosystem:

* **[Pandas & NumPy]** - High-performance data manipulation and numerical computing.
* **[Arch]** - Specialized library for estimating AutoRegressive Conditional Heteroskedasticity (ARCH) models.
* **[YFinance]** - Reliable historical market data extraction.
* **[Matplotlib & Seaborn]** - Advanced data visualization.

---

## 🚀 Getting Started

Follow these steps to run the simulation locally on your machine.

### 1. Prerequisites
Ensure you have Python installed, then install the required packages:
```bash
pip install numpy pandas yfinance arch matplotlib seaborn
```

### 2. Execution
Clone the repository, navigate to the folder, and launch Jupyter:
```bash
git clone https://github.com/arpittripathi4298/infosys-tarch-simulation.git
cd infosys-tarch-simulation
jupyter notebook
```

### 3. Run the Analysis
Open **"TARCH Model for Infosys.ipynb"** and execute the cells sequentially. 

---

## 📊 What You Will See

Running the final cell generates a beautiful, dark-themed analytical dashboard featuring:
1. **Volatility Overlay:** A comparison of absolute realized returns versus the TARCH conditional volatility.
2. **Price Prediction:** 100 sample simulated price paths layered under the *Expected Average Price* trendline.
3. **Projected Variance:** The next 30 days of simulated volatility trajectories highlighting the expected mean path.

---

## ⚠️ Disclaimer

> **Note:** The methodologies and code provided in this repository are strictly for academic, educational, and research purposes. Financial markets are subject to random, unpredictable events. This model does not constitute financial advice, and the simulated paths should not be used as the sole basis for live trading or investment decisions.

<div align="center">
  <br>
  <i>If you found this project interesting, please consider giving it a ⭐!</i>
</div>
