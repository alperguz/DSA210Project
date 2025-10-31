Correlation Between Premier League Players’ Market Values and Performance Statistics

Project Idea
This project aims to investigate the relationship between Premier League players’ performance statistics (such as goals, assists, pass accuracy, and defensive actions) and their end-of-season market values. I hypothesize that players with stronger on-field performance metrics will tend to have higher market valuations, though the strength of correlation may vary by position. By analyzing player data from public football databases like Transfermarkt and FBref, I intend to identify which performance indicators most strongly influence market value and whether certain player roles (e.g., attackers vs. defenders) exhibit different valuation patterns.


## 📂 Data Sources
1. **Player Market Values:** [Transfermarkt](https://www.transfermarkt.com/) — end-of-season market values  
2. **Performance Statistics:** [FBref](https://www.kaggle.com/datasets/siddhrajthakor/fbref-premier-league-202425-player-stats-dataset?resource=download) — season-level performance metrics (goals, assists, passes, tackles, etc.)  

**Data Enrichment:**  
Combine both sources using player name and season. Optionally add team-level data (league position, points, etc.) for context.

---

## 🧹 Data Preparation
- Use **Python** (with `Requests` and `BeautifulSoup`) for data scraping  
- Clean datasets and merge using Pandas  
- Normalize statistics (per 90 minutes)  
- Store merged data in `.csv` format  

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

