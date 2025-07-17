
# 📊 Indian Futures & Option Stock Pattern Detection System

A robust, automated system designed for detecting patterns in Indian Futures & Options (F&O) stocks. This project utilizes technical indicators, machine learning models, and real-time email alerts to assist traders with advanced signal detection.

---

## 🚀 Features

- ✅ **TA-Lib**-based technical indicator computation (MACD, RSI, Bollinger Bands, etc.)
- 🧠 **Machine Learning** models (Random Forest, Isolation Forest) for signal classification & anomaly detection
- ⏰ Automated execution and scheduling using the `schedule` library
- 📩 Email alerts for key trade signals or unusual movements
- 📉 Smoothed peak detection using **Savitzky-Golay filters**
- 📥 Real-time data fetching via **Yahoo Finance**

---

## 🛠️ Tech Stack

| Category            | Libraries/Tools Used                                      |
|---------------------|-----------------------------------------------------------|
| Language            | Python                                                    |
| Data Fetching       | `yfinance`, `yahoo_fin`                                   |
| Data Analysis       | `pandas`, `numpy`, `scipy`, `ta-lib`, `ta`                |
| Machine Learning    | `scikit-learn` (Random Forest, Isolation Forest)          |
| Visualization       | `matplotlib`, `seaborn`                                   |
| Automation          | `schedule`, `time`, `datetime`                            |
| Communication       | `smtplib`, `email.mime` (for alerts)                      |

---

## 📦 Installation

### Required Python Packages

```bash
pip install yfinance yahoo_fin schedule ta scikit-learn matplotlib seaborn
```

> ⚠️ **TA-Lib** may require system-level dependencies. Use `conda` if available:

```bash
# Best way to install TA-Lib (recommended)
conda install -c conda-forge ta-lib
```

---

## 🧠 How It Works

1. **Fetches F&O stock data** from Yahoo Finance.
2. **Computes technical indicators** like RSI, MACD, Bollinger Bands.
3. **Detects patterns** using peak finding and smoothing filters.
4. **Uses ML models** to classify buy/sell signals and detect anomalies.
5. **Sends email alerts** when patterns match high-confidence criteria.
6. **Runs on a schedule** to automate checks throughout the trading day.

---

## 📈 Example Use Cases

- Swing or positional trading in Indian equity F&O segment
- Automated signal generation using hybrid ML + TA strategies
- Risk management using Isolation Forest anomaly detection

---

## 📬 Alerts & Notifications

This system can email signals such as:

- "Strong Buy/Sell" conditions
- Unusual price/volume behavior
- Detected breakout patterns

---

## 📎 File Info

- `Indian_Futures_&_Option_Stock_Pattern_Detection_System.ipynb`: Main notebook containing full implementation

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**. It does not constitute financial advice. Trading involves risk.

---

## 📧 Contact
Email- sarthakkadam.ai@gmail.com
For suggestions or collaboration, feel free to open an issue or contact the author.
