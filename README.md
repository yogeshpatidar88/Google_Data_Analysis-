# 🚀 Google Trends Data Analysis Project

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Made with Love](https://img.shields.io/badge/Made%20with-Love-red.svg)]()

---

> This project leverages the **Python ecosystem** to harness Google Trends data for insightful analysis of search interest — enabling effective market research and trend identification.  
> It answers key business questions about geographical popularity and historical trend comparison for user-defined keywords.

---

## 🛠️ Key Technologies

| Technology | Role in Project |
|---|---|
| **pytrends** | Interface for accessing and fetching data from the Google Trends API |
| **pandas** | Core library for data manipulation and preparing data for visualization |
| **matplotlib & seaborn** | Static, publication-ready line plots and horizontal bar charts |
| **plotly.express** | Interactive geographical visualizations (Choropleth maps) |

---

## 🎯 Analysis Scope & Flexibility

The codebase is designed for **easy adaptability**. Change two variables to analyze any topic:

- `PRIMARY_KEYWORD` — main term used for geographic popularity and historical trend analysis.  
- `COMPARISON_KEYWORDS` — list of related terms used for time-based comparisons.

---

## 📊 Project Outputs & Visualizations

The script performs five analytical tasks and produces four visual outputs:

### 1. Code Flexibility (Core Design)
- Driven by `PRIMARY_KEYWORD` and `COMPARISON_KEYWORDS`.  
- Reusable across domains.

### 2 & 3. Geographical Interest Analysis
**Task:** Find where the `PRIMARY_KEYWORD` is most searched worldwide.

- **Output 1 — Top 15 Countries Bar Plot (Seaborn)**  
  Horizontal bar chart ranking the top 15 countries by relative interest.

- **Output 2 — Global Interest Choropleth Map (Plotly Express)**  
  Interactive world map shading countries by interest score.

### 4. Time-Wise Interest Extraction (Single Trend)
**Task:** Visualize the `PRIMARY_KEYWORD` historical trend.

- **Output 3 — Single Trend Line Plot (Matplotlib)**  
  Line chart showing relative popularity over time (e.g., last 5 years).

### 5. Compare Related Keywords
**Task:** Compare search interest across `COMPARISON_KEYWORDS`.

- **Output 4 — Keyword Comparison Plot (Matplotlib)**  
  Multi-line plot showing all keywords on the same axes.

---

## ⚙️ Quick Start

1. **Clone**
```bash
git clone https://github.com/<your-username>/google-trends-analysis.git
cd google-trends-analysis
