# Correlation Between Premier League Players’ Market Values and Performance Statistics

## Project Idea
This project aims to investigate the relationship between Premier League players’ performance statistics (such as goals, assists, pass accuracy, and defensive actions) and their end-of-season market values. I hypothesize that players with stronger on-field performance metrics will tend to have higher market valuations, though the strength of correlation may vary by position. By analyzing player data from public football databases like Transfermarkt and FBref, I intend to identify which performance indicators most strongly influence market value and whether certain player roles (e.g., attackers vs. defenders) exhibit different valuation patterns.

---

## Description of Dataset
The project will utilize two primary datasets:

**Player Market Value Dataset:**  

- Player Name: The name of each Premier League player included in the dataset.
- Market Value (€): The estimated market value of the player at the end of the season, as recorded on Transfermarkt.
- Club Name: The Premier League team the player was registered with during the season.
- Player Position: The position category of the player (e.g., Forward, Midfielder, Defender, Goalkeeper).
- Season: The season year corresponding to the player’s market valuation.
- Age: The age of the player at the end of the season.

**Player Performance Statistics Dataset:**  

- Goals Scored: Total number of goals scored by the player during the season.
- Assists: Total number of assists provided by the player.
- Minutes Played: The total number of minutes the player was on the field.
- Pass Accuracy (%): Percentage of successful passes out of total attempted passes.
- Tackles and Interceptions: Defensive metrics representing ball recoveries and challenges won.
- Expected Goals (xG) and Expected Assists (xA): Advanced performance metrics representing quality of chances created or taken.
- Club Performance: Team-level features such as league position or total team points for contextual analysis.

---

## Plan

**Data Collection**

- Player Market Value Data Sources:
Transfermarkt — for collecting end-of-season player market values, including player name, club, position, age, and estimated value in euros.

- Player Performance Statistics Data Source:
Kaggle – FBref Premier League 2024/25 Player Stats Dataset — for gathering player-level match performance metrics such as goals, assists, minutes played, xG, xA, pass accuracy, and defensive statistics.

**Data Analysis Approach**

- Exploratory Data Analysis (EDA)
  
- Summary statistics and visual exploration of player performance metrics.
  
- Scatter plots comparing player statistics to market value.

- Correlation matrices to identify which performance variables are most strongly associated with value.
  
- Position-based segmentation (Forwards, Midfielders, Defenders, Goalkeepers) to examine role-specific trends.

*Statistical Analysis*

- Pearson and Spearman correlation tests to measure the strength and direction of relationships between market value and performance indicators.
- Multiple linear regression models to estimate how different variables (e.g., goals, assists, minutes played) influence a player’s valuation.
- Feature importance analysis to identify which statistics have the greatest predictive power.

*Visualization and Presentation*

- Bar charts and scatter plots illustrating relationships between performance metrics and market value.
Heatmaps showing correlations across variables.
- Positional comparison tables summarizing key statistical findings.
- Optional interactive visualizations using Plotly or Seaborn.

---

# Tools and Technologies

- Python: Main programming language for data analysis and visualization.

- Pandas & NumPy: For data manipulation, cleaning, and numerical calculations.

- Matplotlib & Seaborn: For creating visualizations and statistical graphics.

- Scikit-learn & Statsmodels: For regression analysis and modeling.

- Jupyter Notebooks: For documenting and presenting the full analysis workflow.

---

# Expected Outcomes

- Identification of statistically significant relationships between player performance metrics (such as goals, assists, and pass accuracy) and end-of-season market values.

- Assessment of which performance statistics have the strongest influence on player valuation across different positions.

- Development of a regression-based model that predicts a player’s estimated market value using statistical and performance data.

- Insight into how positional roles (forwards, midfielders, defenders, goalkeepers) affect valuation patterns.

- A framework for future research into data-driven valuation modeling in professional football analytics.

---

# Potential Challenges

- Inconsistencies in data collection and reporting between sources (Transfermarkt vs. FBref).

- Missing or incomplete statistics for certain players (e.g., substitutes or injured players).

- Difficulty in controlling for non-performance factors (such as player age, contract length, or reputation).

- Distinguishing correlation from causation — high-performing players may attract higher market values due to external factors.

- Handling potential data bias in market value estimates (media attention or transfer rumors may inflate values).

---
