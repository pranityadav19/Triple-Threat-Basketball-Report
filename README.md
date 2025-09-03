# Triple Threat Basketball Report

A data analysis project exploring the relationship between **three-point shooting** and **NBA regular season wins** over the past 10 years.

---

## 📌 Project Overview
- **Goal**: Understand how much the three-point shot affects the number of wins an NBA team earns in the regular season.  
- **Research Questions**:
  1. Does being in the top 15 in the league in three-point percentage increase regular season wins?  
  2. Does the number of three-pointers made per game affect a team’s win total?

---

## 🗂 Dataset & Methods
- **Data Collected**:  
  - Sampled 100 NBA teams across the 2012–2023 seasons (random selection from 300 teams).  
  - Sources:  
    - Wins per season: *StatMuse.com*  
    - Three-pointers made per game: *TeamRankings.com*  
    - Three-point percentage rankings: *TeamRankings.com*
- **Sampling**: Random number generator used to pick teams by power rankings each year.  
- **Analysis**:  
  - Histograms to check normality of wins and 3PM distributions.  
  - Scatterplots for correlation.  
  - Boxplots to compare wins between top-15 and non-top-15 3PT% teams.  
  - Regression model using predictors:  
    - Top 15 in 3PT% (categorical)  
    - Three-pointers made per game (numeric):contentReference[oaicite:2]{index=2}

---

## 📊 Results
- **Regression Findings**:
  - Being in the top 15 in 3PT% is a **significant predictor** of wins (p < 0.05).  
  - Average 3-pointers made per game was **not significant**.  
  - Model explained **16.39% of variance** in regular season wins (Adjusted R² = 0.1639).

**Key Tables**:
- **Median Wins**: 45.5 (IQR = 11.25)  
- **Median 3PM**: 10.7 (IQR = 3.65)  
- **Top 15 in 3PT%**: 52 teams Yes / 48 teams No

---

## 🔑 Insights
- Teams shooting efficiently from three (Top 15 in 3PT%) **win more games**, regardless of total 3-pointers made.  
- Simply shooting more threes doesn’t guarantee wins without efficiency.  
- The evolution of basketball (post-2015 Warriors era) likely changed dynamics, making threes more important in recent years.

---

## ⚠️ Limitations
- Data spans 10 years, but the NBA changed significantly after the 2015–2016 Warriors’ three-point revolution.  
- Older data (2012–2015) may weaken relationships since the league hadn’t fully adopted modern spacing and shooting yet.

---

## 🔮 Future Research
- Analyze playoff performance instead of regular season wins.  
- Restrict dataset to the past 7 years to reflect the **modern NBA era**.  
- Compare results across different eras of basketball (pre-2015 vs. post-2015).  
- Study the effect of star shooters (e.g., Stephen Curry) on team construction and league trends.
