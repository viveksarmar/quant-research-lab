# quant-research-lab

Core quant research repo â€” backtesting, portfolio construction, factor analysis, PnL attribution.

## Structure
- `data/`       â€” sample or synthetic datasets used for backtests
- `notebooks/`  â€” Jupyter notebooks demonstrating workflows and results
- `strategies/` â€” self-contained strategy implementations (momentum, mean-reversion)
- `backtests/`  â€” backtest engine and parameter sweep scripts
- `analytics/`  â€” PnL decomposition, drawdowns, exposures, risk metrics
- `utils/`      â€” helper functions (returns, rolling stats, plotting)
- `reports/`    â€” exported charts and PDF reports
- `tests/`      â€” unit tests for reproducibility

## Quickstart
1. Create a Python env (optional): `python -m venv .venv`
2. Install deps: `pip install -r requirements.txt`
3. Open `notebooks/` in Jupyter Lab
