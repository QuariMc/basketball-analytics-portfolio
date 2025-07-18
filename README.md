# 🏀 Underrated NBA Players – Analytics Project

This project uses advanced NBA statistics to identify underrated players who make a big impact with relatively low usage.

We use a custom **Impact Score** calculated from:
- **Box Plus Minus (BPM)**
- **Win Shares (WS)**
- **Value Over Replacement Player (VORP)**
- **Usage Percentage (USG%)**

---

## 📊 Tools Used
- **Python** (Pandas, Seaborn, Matplotlib)
- **Jupyter Notebook**
- **Basketball Reference** for data

---

## 🧮 Impact Score Formula
```python
Impact Score = (BPM + WS + VORP) / USG%
