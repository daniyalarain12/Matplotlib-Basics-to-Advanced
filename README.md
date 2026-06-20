# 📊 Matplotlib — Basics to Advanced

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.x-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

> A complete Matplotlib learning repository — from basic plots to advanced subplots and OOP API — with real-world data analysis projects.

---

## 📁 Repository Structure

```
Matplotlib-Basics-to-Advanced/
│
├── Matplotlib-Topics/
│   ├── 01_Line_Plot.ipynb
│   ├── 02_Bar_Chart.ipynb
│   ├── 03_Pie_Chart.ipynb
│   ├── 04_Histogram.ipynb
│   ├── 05_Scatter_Plot.ipynb
│   ├── 06_Stack_Plot.ipynb
│   ├── 07_Box_Plot.ipynb
│   ├── 08_Subplot.ipynb
│   └── 09_Subplots_and_OOP_API.ipynb
│
└── Projects/
    ├── Datasets/
    │   ├── fifa_data.csv
    │   └── gas_prices.csv
    ├── 01_Gas_Prices_Analysis.ipynb
    └── 02_FIFA_2018_Player_Analysis.ipynb
```

---

## 📚 Topics Covered

| # | Notebook | Key Concepts |
|---|----------|-------------|
| 01 | Line Plot | `plt.plot()`, linestyle, markers, grid, limits, ticks, savefig, styles |
| 02 | Bar Chart | `plt.bar()`, `plt.barh()`, grouped bars, `plt.text()`, `np.arange()` |
| 03 | Pie Chart | `plt.pie()`, autopct, explode, shadow, startangle, wedgeprops |
| 04 | Histogram | `plt.hist()`, bins, custom bins, overlapping histograms, `axvline` |
| 05 | Scatter Plot | `plt.scatter()`, cmap, colorbar, bubble effect, annotations, multi-group |
| 06 | Stack Plot | `plt.stackplot()`, layered data, cumulative visualization |
| 07 | Box Plot | `plt.boxplot()`, IQR, outliers, whiskers, showmeans, multi-group comparison |
| 08 | Subplot | `plt.subplot()`, grid layout, `tight_layout()` |
| 09 | Subplots & OOP API | `plt.subplots()`, fig/ax, `set_` methods, `sup` methods, Pyplot vs OOP API |

---

## 🚀 Projects

### 📈 Project 1 — Global Gas Prices Analysis
**File:** `Projects/01_Gas_Prices_Analysis.ipynb`
**Dataset:** `Projects/Datasets/gas_prices.csv`

| Detail | Info |
|--------|------|
| Rows | 19 (years 1990–2008) |
| Columns | 11 (Year + 10 countries) |
| Countries | Australia, Canada, France, Germany, Italy, Japan, Mexico, South Korea, UK, USA |

**Analysis Performed:**
- USA gas price trend over the years
- USA vs Canada vs South Korea price comparison
- Gas price trends for all 10 countries using dynamic plotting
- Focused comparison — Australia, USA, Canada, UK & Japan

**Techniques Used:** Line plots, dynamic plotting with loops, custom xticks, figure sizing

---

### ⚽ Project 2 — FIFA 2018 Player Analysis
**File:** `Projects/02_FIFA_2018_Player_Analysis.ipynb`
**Dataset:** `Projects/Datasets/fifa_data.csv`

| Detail | Info |
|--------|------|
| Rows | 18,207 players |
| Columns | 89 attributes |
| Key Columns Used | Overall, Preferred Foot, Weight, Club |

**Analysis Performed:**
- Distribution of player skill ratings
- Preferred foot breakdown — Left vs Right
- Player weight distribution across 5 categories
- Club comparison — FC Barcelona vs Real Madrid vs New England Revolution

**Techniques Used:** Histogram with custom bins, pie chart with explode, regex data cleaning, box plot

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| **Matplotlib** | All data visualizations |
| **Pandas** | Data loading, filtering and cleaning |
| **NumPy** | Numerical operations and array manipulation |

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/daniyalarain12/Matplotlib-Basics-to-Advanced.git
```

2. Install required libraries
```bash
pip install matplotlib pandas numpy jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

4. Open any notebook from `Matplotlib-Topics/` or `Projects/` folder

---

## 🗺️ My Data Science Learning Journey

This is part of my ongoing Data Science & AI learning roadmap:

| Repository | Status |
|-----------|--------|
| [Python — Basics to Advanced](https://github.com/daniyalarain12/Python-Basics-to-Advanced) | ✅ Completed |
| [NumPy — Basics to Advanced](https://github.com/daniyalarain12/NumPy-Basics-To-Advanced) | ✅ Completed |
| [Pandas — Basics to Advanced](https://github.com/daniyalarain12/Pandas-Basics-to-Advanced) | ✅ Completed |
| **Matplotlib — Basics to Advanced** | ✅ Completed |
| Seaborn — Basics to Advanced | 🔜 Coming Soon |
| Machine Learning | 🔜 Coming Soon |

---

## 📬 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-daniyalarain12-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/daniyalarain12)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniyalarain12)

---

⭐ **If you find this repository helpful, please give it a star!** ⭐
