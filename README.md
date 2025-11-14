# 🌍 FIFA World Cup Data Analysis  
A complete data analysis project on the FIFA World Cup using Python, Pandas, Seaborn, and Matplotlib.  
This project explores trends, patterns, and insights from decades of World Cup history.

---

## 📁 Project Structure

```
Project 2/
│
├── cleaned_data/
│   ├── WorldCups_clean.csv
│   ├── WorldCupMatches_clean.csv
│   └── WorldCupPlayers_clean.csv
│
├── results/
│   ├── 01_top_winning_countries.png
│   ├── 02_goals_per_tournament.png
│   ├── 03_average_goals_per_match.png
│   ├── 04_attendance_over_years.png
│   ├── 05_host_advantage.png
│   ├── 06_most_used_stadiums.png
│   ├── 07_top_cities.png
│   ├── 08_goal_difference_distribution.png
│   ├── 09_top_stages.png
│   ├── 10_top_match_appearances.png
│   ├── 11_correlation_heatmap.png
│   └── 12_lineup_distribution.png
│
├── reports/
│   ├── final_insights.txt
│   └── summary_report.md
│
└── FIFA_WorldCup_Analysis.ipynb
```

---

## 📊 Overview

This project performs a complete data analysis workflow:

### ✔️ Step 1 — Import Data  
Read CSV files for:
- World Cup tournaments  
- Matches  
- Player information  

### ✔️ Step 2 — Data Cleaning  
Fix inconsistencies:
- Convert Year/Attendance formats  
- Remove duplicates  
- Handle missing values  
- Standardize string formatting  

### ✔️ Step 3 — Exploratory Data Analysis (EDA)  
Generated visualizations for:
- Winning teams  
- Goals over time  
- Average goals per match  
- Attendance trends  
- Host-nation advantage  
- Stadium usage  
- City usage  
- Match stage distribution  
- Goal difference distribution  
- Team participation  
- Player lineup analysis  
- Correlation heatmap  

### ✔️ Step 4 — Insights & Findings  
A detailed written summary is provided under `/reports`:

- Brazil is the most successful team  
- Attendance has significantly grown over time  
- Host countries have a measurable advantage  
- Modern World Cups involve far more matches and goals  
- Certain cities and stadiums host more matches than others  
- Wide variance exists in goal differences  
- Biggest recorded victory margin was **X goals**  
- Most frequently played stage is **Round of 16**, etc.  

(See `final_insights.txt` and `summary_report.md` for full insights.)

---

## 📈 Sample Visualizations

Here are some example plots generated in the analysis:

### 🏆 Most Winning Nations
![Top Winning Countries](results/01_top_winning_countries.png)

### ⚽ Goals Over Time
![Goals Per Tournament](results/02_goals_per_tournament.png)

### 🎟️ Attendance Over the Years
![Attendance](results/04_attendance_over_years.png)

*(More visualizations available in the `/results` folder.)*

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📚 Skills Demonstrated

- Data cleaning & preparation  
- Data visualization  
- Exploratory data analysis (EDA)  
- Working with large datasets  
- Trend identification  
- Insight generation  
- Report writing  
- Reproducible analysis in Jupyter  

---

## 📜 How to Use This Notebook

1. Download the notebook:  
   ```
   FIFA_WorldCup_Analysis.ipynb
   ```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open in Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 👤 Author  
**Ayman Abbas Mundol**  
FIFA World Cup Analysis Project  
2025

---

## ⭐ If you found this project useful  
Consider giving the repository a **star ⭐ on GitHub!**
