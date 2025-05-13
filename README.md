# 🚴‍♂️ Sports Analysis: Cycling Race Data

This project explores and analyzes historical cycling race data, focusing on performance trends, team statistics, and factors influencing race outcomes such as time, age, weight, and equipment.

---

## 📝 Overview

The dataset contains records from past cycling race editions including:

- Edition number
- Start date
- Winner name and team
- Distance covered
- Time overall and time margin
- Stage wins and stages led
- Rider's physical attributes (height, weight)
- Age, birth details, nationality, and more

This analysis includes:
- Cleaning missing values and correcting data types
- Visualizing team performance
- Exploring correlations between distance, time, and other rider features
- Identifying key factors affecting race times

---

## 📁 Dataset

The dataset used in this project is loaded from a CSV file named:
sportswinners.csv


Key columns include:
- `edition`, `start_date`, `winner_name`, `winner_team`
- `distance`, `time_overall`, `time_margin`
- `stage_wins`, `stages_led`
- `height`, `weight`, `age`
- `born`, `died`, `birth_town`, `nationality`

---

## 🔍 Key Insights

- **Team Performance:** Teams like *Automoto–Hutchinson* and *La Sportive* had the highest average overall race times.
- **Time vs Distance:** A strong positive correlation exists between total distance and overall race time.
- **Age Distribution:** Cyclists aged 26–35 lead the most stages.
- **Weight Impact:** Lighter bikes appear to improve performance over time.
- **Data Types Fixed:** Dates were converted to proper datetime format.
- **Missing Values Handled:** Nulls in `time_overall`, `height`, and `weight` were filled with median or appropriate values.

---

## 📊 Visualizations

Examples of visualizations included:
- Line plots showing overall time trends over race editions
- Bar charts comparing teams by average time and distance
- Scatter plots showing cyclist weight categories vs. time
- Boxplots analyzing stage leadership across age groups

Libraries used:
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib`, `seaborn`, and `plotly` for visualizations

---

## 🧪 Sample Output

```plaintext
   winner_team           time_overall
0  AD Renting–W-Cup–Bottecchia  87.643056
1  Alcyon–Dunlop               151.257535
2  Astana                      87.897361

sports-analysis/
│
├── sportswinners.csv         # Original dataset
├── sports_analysis.ipynb     # Main Jupyter notebook
└── README.md                 # This file

### 🧑 Author
Mimo Maina
GitHub Repository: Sports_Analysis

### 📄 License
MIT License — see LICENSE for details.
