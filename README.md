# Simple Moving Average (SMA) Crossover Strategy

This project implements a **Simple Moving Average (SMA) Crossover Strategy** in Python.  
It uses a short-term moving average and a long-term moving average to generate **Buy** and **Sell** signals.

---

## Strategy Logic

- **Short SMA**: Average price over a smaller window (e.g., 3 days).  
- **Long SMA**: Average price over a larger window (e.g., 5 days).  
- **Signals**:  
  - **Buy** when the short SMA crosses **above** the long SMA.  
  - **Sell** when the short SMA crosses **below** the long SMA.  

This approach is commonly used in algorithmic trading to capture trend changes.

---
