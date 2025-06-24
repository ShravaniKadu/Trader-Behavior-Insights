# Trader-Behavior-Insights
# 📊 Trader Behavior Insights: Market Sentiment vs. Trader Performance

## 🧠 Overview

This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and historical trader performance on the Hyperliquid exchange. The goal is to uncover behavioral patterns and provide actionable insights that could help shape more intelligent trading strategies.

---

## 🗂️ Datasets Used

### 1. [Bitcoin Fear & Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)
- **Columns:** `date`, `value`, `classification` (e.g., Fear, Greed)

### 2. [Hyperliquid Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)
- **Columns:** `Account`, `Execution Price`, `Closed PnL`, `Side`, `Timestamp`, `Size USD`, etc.

---

## ⚙️ Methodology

1. **Data Cleaning & Preprocessing**
   - Parsed and aligned timestamps.
   - Merged trader data with sentiment classification based on trade date.

2. **Feature Engineering**
   - Daily trade metrics calculated: win rate, average PnL, trade size.

3. **Exploratory Data Analysis (EDA)**
   - Bar plots, box plots, and time-series analysis to compare metrics across sentiments.

4. **Insights Generation**
   - Identified trading behavior trends related to market sentiment shifts.

---

## 📈 Key Insights

- ✅ **Win Rate Increases During Greed:** Trader win rates peaked during “Extreme Greed” periods, suggesting higher confidence or stronger market trends.
- ⚠️ **Larger Losses During Fear:** Box plots show higher variance in losses during “Fear” days, indicating risky or uncertain environments.
- 💰 **Higher Trade Sizes in Greedy Markets:** Average trade size increased during “Greed” phases, implying elevated risk appetite.

---

## 📁 Project Structure

