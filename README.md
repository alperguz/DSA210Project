# Correlation Between Premier League Players’ Market Values and Performance Statistics

---

## Project Idea
This project aims to investigate the relationship between Premier League players’ performance statistics (such as goals, assists, pass accuracy, and defensive actions) and their end-of-season market values. I hypothesize that players with stronger on-field performance metrics will tend to have higher market valuations, though the strength of correlation may vary by position. By analyzing player data from public football databases like Transfermarkt and FBref, I intend to identify which performance indicators most strongly influence market value and whether certain player roles (e.g., attackers vs. defenders) exhibit different valuation patterns.

---

## Description of Dataset
The project will utilize two primary datasets:

**Player Market Value Dataset:**  

Player Name: The name of each Premier League player included in the dataset.
Market Value (€): The estimated market value of the player at the end of the season, as recorded on Transfermarkt.
Club Name: The Premier League team the player was registered with during the season.
Player Position: The position category of the player (e.g., Forward, Midfielder, Defender, Goalkeeper).
Season: The season year corresponding to the player’s market valuation.
Age: The age of the player at the end of the season.

**Player Performance Statistics Dataset:**  

Goals Scored: Total number of goals scored by the player during the season.
Assists: Total number of assists provided by the player.
Minutes Played: The total number of minutes the player was on the field.
Pass Accuracy (%): Percentage of successful passes out of total attempted passes.
Tackles and Interceptions: Defensive metrics representing ball recoveries and challenges won.
Expected Goals (xG) and Expected Assists (xA): Advanced performance metrics representing quality of chances created or taken.
Club Performance: Team-level features such as league position or total team points for contextual analysis.

---

## Plan

---
**Data Collection**

Player Market Value Data Sources:
Transfermarkt — for collecting end-of-season player market values, including player name, club, position, age, and estimated value in euros.

Player Performance Statistics Data Source:
Kaggle – FBref Premier League 2024/25 Player Stats Dataset — for gathering player-level match performance metrics such as goals, assists, minutes played, xG, xA, pass accuracy, and defensive statistics.

**Data Analysis Approach**

Exploratory Data Analysis (EDA)

Summary statistics and visual exploration of player performance metrics.
Scatter plots comparing player statistics to market value.

Correlation matrices to identify which performance variables are most strongly associated with value.
Position-based segmentation (Forwards, Midfielders, Defenders, Goalkeepers) to examine role-specific trends.

*Statistical Analysis*

Pearson and Spearman correlation tests to measure the strength and direction of relationships between market value and performance indicators.

Multiple linear regression models to estimate how different variables (e.g., goals, assists, minutes played) influence a player’s valuation.
Feature importance analysis to identify which statistics have the greatest predictive power.

*Visualization and Presentation*

Bar charts and scatter plots illustrating relationships between performance metrics and market value.
Heatmaps showing correlations across variables.

Positional comparison tables summarizing key statistical findings.

Optional interactive visualizations using Plotly or Seaborn.

**Tools and Technologies**

Python: Main programming language for data analysis and visualization.
Pandas & NumPy: For data manipulation, cleaning, and numerical calculations.
Matplotlib & Seaborn: For creating visualizations and statistical graphics.
Scikit-learn & Statsmodels: For regression analysis and modeling.
Jupyter Notebooks: For documenting and presenting the full analysis workflow.

---

## 🔍 Analysis Plan
1. **Exploratory Data Analysis (EDA)**  
   - Distribution of player values by position  
   - Correlation matrix between market value and performance stats  
   - Scatter plots (e.g., goals vs. market value)

2. **Statistical Tests**  
   - Pearson and Spearman correlation tests  

3. **Modeling (optional)**  
   - Multiple Linear Regression to estimate which stats influence market value  

---

## 📊 Expected Results
- Offensive players’ values likely correlate strongly with goals and assists  
- Defensive or goalkeeper metrics may influence value differently  
- Age and potential may add hidden variance not captured by statistics  

---

## ⚙️ Tools & Libraries
Python • Pandas • NumPy • Matplotlib • Seaborn • Scikit-learn • Statsmodels • BeautifulSoup • Requests  

---

## 🗓️ Timeline

| Date | Task |
|------|------|
| Oct 31 | Submit project proposal (README.md) |
| Nov 28 | Data collection and EDA |
| Jan 2 | Apply regression models |
| Jan 9 | Final submission |

---

## 🤝 Academic Integrity & AI Usage
Parts of this README (structure and phrasing) were created with the help of **ChatGPT (GPT-5)**.  
All data collection, coding, and analysis will be performed independently by **Muhammed Emir Acar**.
