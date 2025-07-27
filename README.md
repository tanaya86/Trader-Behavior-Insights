# Bitcoin Sentiment vs Trader Performance Analysis

## 📊 Project Overview

This project explores the **relationship between market sentiment (Fear/Greed)** and **trader performance** using two datasets:

1. **Bitcoin Market Sentiment Dataset**
   - Columns: `Date`, `Classification` (Fear/Greed)

2. **Historical Trader Data from Hyperliquid**
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

## 🧠 Objectives

### 1. Analyze Relationship Between Sentiment and Performance
- Merge both datasets on date.
- Compare average `closedPnL` and win rate under "Fear" vs. "Greed".
- Perform statistical tests to verify correlation or significance.

### 2. Uncover Hidden Patterns in Trader Behavior
- Cluster traders based on attributes (e.g., leverage, side, symbol).
- Analyze behavioral shifts across sentiment changes.
- Visualize trade timing, size, and outcome patterns.

### 3. Deliver Actionable Insights
- Recommend trading strategies aligned with sentiment shifts.
- Identify high-performing trader archetypes and their conditions.
- Suggest optimal trade conditions (timing, leverage, sentiment state).



