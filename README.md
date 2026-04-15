# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Objective
This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

## 📂 Datasets Used
1. Bitcoin Market Sentiment (Fear/Greed Index)
2. Historical Trader Data (Hyperliquid)

---

## ⚙️ Methodology

### 1. Data Preparation
- Cleaned column names
- Converted timestamps to datetime
- Extracted daily-level data
- Merged trader data with sentiment data on date

### 2. Feature Engineering
- Daily Profit & Loss (PnL)
- Win/Loss indicator
- Trade size (used as proxy for risk)
- Trade frequency

### 3. Analysis Performed
- PnL comparison across Fear vs Greed
- Trade size behavior by sentiment
- Trading activity (number of trades)
- Long/Short distribution

---

## 📊 Key Insights

1. **Higher Profitability During Greed**
   Traders tend to generate higher average profits during Greed periods compared to Fear periods.

2. **Increased Risk-Taking in Greed**
   Trade sizes are significantly larger during Greed, indicating higher risk appetite.

3. **Higher Market Activity in Greed**
   Trading frequency increases during Greed, suggesting more active participation.

---

## 💡 Strategy Recommendations

### 1. Risk Management Strategy
During Fear periods, traders should reduce trade sizes to minimize potential losses due to uncertain market conditions.

### 2. Controlled Aggression Strategy
During Greed periods, traders can increase activity but should avoid overtrading and maintain disciplined risk management.

---

## ⚠️ Note
Leverage data was not available in the dataset. Therefore, trade size (size USD) was used as a proxy for risk exposure.

---

## 🚀 How to Run

1. Clone the repository:
Download ipynb file/notebook

2. Install dependencies:
pip install pandas numpy matplotlib seaborn

3. Run the notebook:
jupyter notebook


