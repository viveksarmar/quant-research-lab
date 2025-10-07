# Quant Research Lab 🧮  
Research Framework for Systematic Portfolio Management, Backtesting, and Risk Attribution  

---

## 🔍 Overview
This repository serves as a **research and prototyping environment** for systematic trading and portfolio analytics.  
It focuses on translating financial hypotheses into data-driven strategies that can be backtested, stress-tested, and benchmarked for risk-adjusted performance.

---

## 🎯 Objectives
- Design and evaluate **cross-sectional and time-series strategies**  
- Perform **PnL attribution, factor decomposition**, and **drawdown analysis**  
- Build a reusable and modular **backtesting engine**  
- Visualize portfolio exposures, rolling risk metrics, and trade-level analytics  

---

## 📁 Repository Structure
| Folder | Description |
|--------|--------------|
| `data/` | Sample datasets or synthetic time series used for backtesting |
| `notebooks/` | Research notebooks with documented workflows and visualizations |
| `strategies/` | Implementation of quant strategies (momentum, carry, factor models) |
| `backtests/` | Backtesting framework, simulations, and trade-level analytics |
| `analytics/` | PnL decomposition, exposure heatmaps, drawdown studies |
| `utils/` | Helper functions for statistics, plotting, and performance metrics |
| `reports/` | Generated charts, summary tables, and final PDF reports |
| `tests/` | Unit tests for reproducibility and verification of computations |

---

## 🧰 Tech Stack
- **Languages:** Python (Pandas, Numpy, Scipy)  
- **Analytics:** Statsmodels, PyPortfolioOpt  
- **Visualization:** Matplotlib, Plotly, Seaborn  
- **Testing:** Pytest  

---

## 🚀 Quickstart
```bash
# (1) Optional: create and activate virtual env
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# (2) Install dependencies
pip install -r requirements.txt

# (3) Launch research notebooks
jupyter lab
