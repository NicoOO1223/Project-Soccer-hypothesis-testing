# ⚽ FIFA Score Analysis

This project compares match scores between **men’s and women’s FIFA World Cup tournaments** using statistical analysis in Python.

---

## 📌 Project Overview

- Data: `men_results.csv` and `women_results.csv`
- Goal: Compare total match scores (home + away) between men’s and women’s tournaments since 2002
- Approach:
  1. Filter FIFA World Cup matches from 2002 onward
  2. Compute total score for each match
  3. Visualize score distributions using histograms
  4. Test for normality with Shapiro-Wilk test
  5. Perform **Mann-Whitney U test** to compare distributions

---

## 🛠️ Tech Stack

- **Python** – scripting and analysis  
- **Pandas** – data manipulation  
- **Matplotlib / Seaborn** – visualization  
- **SciPy** – statistical tests  

---

## 📈 Analysis Steps

1. **Data preprocessing**: Filter by tournament and date  
2. **Feature engineering**: Calculate `total_score` = home + away  
3. **Visualization**: Plot histograms of total scores  
4. **Normality check**: Shapiro-Wilk test  
5. **Comparison test**: Mann-Whitney U test  
6. **Interpret results**: Determine if women’s matches tend to have higher scores  

---
