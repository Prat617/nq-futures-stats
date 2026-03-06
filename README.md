# NQ Futures CME — Comprehensive Statistics & Research Database

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A curated collection of **Nasdaq-100 E-mini (NQ) Futures** datasets, statistics, and research tools. This repository serves as a comprehensive database for NQ futures data sourced from the **CME Group**, enabling quantitative analysis, backtesting, and market research.

---

## 📁 Directory Structure

```
nq-futures-stats/
├── data/
│   ├── raw/              # Raw downloaded datasets
│   ├── processed/        # Cleaned and transformed datasets
│   └── reference/        # Reference data (contract specs, calendars)
├── scripts/              # Python scripts for data collection
├── notebooks/            # Jupyter notebooks for analysis
├── docs/                 # Documentation and research notes
├── config/               # Configuration files
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## 📊 Datasets

| Dataset | Description | Format |
|---------|-------------|--------|
| Daily OHLCV | Open, High, Low, Close, Volume | CSV / Parquet |
| Session Statistics | RTH and ETH session stats | CSV |
| Volume Profiles | TPO and volume-at-price | CSV |
| Contract Specifications | Tick size, trading hours, margins | JSON |

## 🚀 Getting Started

```bash
git clone https://github.com/Prat617/nq-futures-stats.git
cd nq-futures-stats
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
cp config/settings.example.yaml config/settings.yaml
```

## 📈 Data Sources

- **CME Group** — E-mini Nasdaq-100 futures (NQ)
- Exchange: CME Globex
- Trading Hours: Sunday–Friday, 5:00 pm – 4:00 pm CT

## 🤝 Contributing

Fork the repo, create a feature branch, and open a Pull Request.

## 📜 License

MIT License — see [LICENSE](LICENSE).

## ⚠️ Disclaimer

For educational and research purposes only. Trading futures involves substantial risk.
