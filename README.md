# PrimeTrade Market Sentiment Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using:

- Bitcoin Fear & Greed Index Dataset
- Hyperliquid Historical Trader Data

The goal is to identify how market sentiment influences trading behavior, profitability, trade direction, and overall trader performance.

---

## Problem Statement

Market sentiment often drives investor behavior and can significantly impact trading outcomes.

This project investigates:

- How trader profitability changes during Fear and Greed periods
- Whether Long or Short positions perform better under different market conditions
- Which assets generate the highest profits
- How trader behavior changes with sentiment
- Actionable insights for sentiment-aware trading strategies

---

## Datasets

### 1. Bitcoin Fear & Greed Index

Contains:

- Date
- Sentiment Classification
    - Extreme Fear
    - Fear
    - Neutral
    - Greed
    - Extreme Greed

### 2. Hyperliquid Historical Trader Data

Contains:

- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side
- Timestamp
- Direction
- Closed PnL
- Transaction Details

---

## Project Workflow

### Data Cleaning

- Converted timestamps to datetime format
- Extracted trading dates
- Handled missing values
- Standardized sentiment labels

### Data Integration

Merged:

- Historical Trading Data
- Fear & Greed Index

Using trading dates as the common key.

### Exploratory Data Analysis (EDA)

Analyzed:

- Profitability by sentiment
- Win rate by sentiment
- Trade size by sentiment
- Long vs Short performance
- Monthly profitability trends
- Top-performing traders
- Most profitable coins

---

## Visualizations

### Long vs Short PnL by Sentiment

Compares profitability of long and short positions under different market conditions.

### Monthly PnL vs Fear & Greed Index

Tracks profitability alongside market sentiment over time.

### Top 10 Most Profitable Coins

Identifies the assets contributing the highest realized profits.

### Top 10 Traders by Closed PnL

Ranks traders based on cumulative realized profit.

### PnL Distribution by Market Sentiment

Examines the spread and volatility of profits across market conditions.

---

## Key Insights

### 1. Sentiment Influences Trading Performance

Trader profitability varies across different market sentiment conditions.

### 2. Trade Direction Matters

Long and short positions perform differently depending on whether markets are driven by fear or greed.

### 3. Asset Concentration

A small number of assets contribute a significant share of total profits.

### 4. Performance Concentration

Top traders generate a disproportionate amount of overall profitability.

### 5. Market Psychology Impacts Outcomes

Fear and Greed conditions influence trading behavior, position sizing, and profitability.

---

## Recommendations

- Use market sentiment as an additional trading signal.
- Favor strategies aligned with prevailing market psychology.
- Monitor Fear & Greed trends before increasing exposure.
- Focus on historically profitable assets.
- Apply stricter risk management during extreme sentiment conditions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Repository Structure

```text
PrimeTrade-Sentiment-Trading-Analysis/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── notebook/
│   └── PrimeTrade_Market_Sentiment_Analysis.ipynb
│
├── outputs/
│   ├── charts/
│   └── report.pdf
│
├── README.md
└── requirements.txt
```

---

## How to Run

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
PrimeTrade_Market_Sentiment_Analysis.ipynb
```

Run all cells sequentially.

---

## Author

**Sidhartha Malla**

Data Science | Analytics | Machine Learning

