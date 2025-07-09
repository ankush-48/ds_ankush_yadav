# 🚀 Web3 Trading Behavior vs Market Sentiment Analysis

A deep-dive analysis into how trader behavior aligns—or diverges—from overall crypto market sentiment using real Hyperliquid trading data and the Bitcoin Fear & Greed Index.

---

## 🎯 Objective

To investigate the relationship between **trader behavior** (profitability, volume, risk exposure) and **market sentiment** (Fear vs Greed) in the crypto trading space. The goal is to uncover whether traders behave rationally or emotionally during different sentiment phases and derive actionable insights that can lead to **smarter, sentiment-aware trading strategies**.

---

## 📦 Repository Structure

ds_ankush_yadav/
├── notebook_1.ipynb # 📓 Main Google Colab notebook (analysis + visuals)
├── csv_files/
│ ├── historical_data.csv # Raw Hyperliquid trading data
│ ├── fear_greed_index.csv # Bitcoin Fear & Greed Index
│ └── processed_data.csv # Cleaned, date-aligned, merged dataset
├── outputs/
│ ├── volume_vs_sentiment.png # Trade volume vs sentiment class
│ ├── pnl_vs_sentiment.png # Average profitability vs sentiment class
│ └── traders_vs_index.png # Trader participation vs sentiment score
├── ds_report.pdf # 📄 Final insights summary (ready for review)
└── README.md # 📘 You’re here

---

## 📊 Key Insights

- 🟢 **Volume spikes during Greed**, but profitability **often drops**, suggesting crowd-driven overtrading.
- 🟡 **Fear phases show reduced volume**, yet some traders achieve better average PnL — likely due to strategic or contrarian trading.
- 🔵 **Trader participation** closely follows sentiment levels — crowd psychology is a real market driver.
- 🔴 **High start positions during Greed** hint at overconfidence and riskier trades during market euphoria.

---

## 🧠 Strategic Implications

- **Greed may signal caution**: Overconfident traders take poor positions.
- **Fear may signal opportunity**: Less crowded entries, higher risk-adjusted return.
- **Use sentiment as a filter**, not a signal: Combine sentiment with metrics like volume and trader count.

---

## ▶️ How to Reproduce

1. Clone this repo or download the ZIP.
2. Open `notebook_1.ipynb` in [Google Colab](https://colab.research.google.com/).
3. Upload the files in `csv_files/` if prompted.
4. Run all cells to generate:
   - Merged dataset (`processed_data.csv`)
   - Visuals (saved to `outputs/`)
   - Insights for strategic trading

---

## 📌 Dataset Sources

- **[Fear & Greed Index](https://alternative.me/crypto/fear-and-greed-index/)**  
- **Hyperliquid Trader Data** (Provided)

---

## 👤 Author

**Ankush Yadav**  
This project was completed as part of the Web3 Trading Data Science project.  
Assisted by ChatGPT for data wrangling, insights, and documentation.

---

## 🏁 Final Notes

This project showcases real-world data science skills:
- 🧹 Data cleaning & merging  
- 📈 Behavioral analytics  
- 🧭 Market psychology interpretation  
- 📑 Clear reporting & visualization

 **thank you for your time**!


