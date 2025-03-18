# T20 Cricket Innings Analysis (India vs USA)
![Alt text](https://github.com/Khushi-Bafana/T20-World-Cup-Statistics-and-Predictive-Analysis/blob/main/T20%20analysis%20image%20for%20github.jpg)

## Project Overview
This project analyzes ball-by-ball data from a T20 cricket match between India and the USA. The objective is to derive meaningful insights from batting, bowling, and over-wise trends using **Exploratory Data Analysis (EDA)**.

## Objectives
- Identify **top-performing batters and bowlers**.
- Analyze **scoring patterns and bowling economy rates**.
- Understand **match strategies** in different phases (Powerplay, Middle Overs, Death Overs).
- Investigate **wicket trends and player performances**.

## Purpose
This project aims to provide a **data-driven understanding of player performances and game strategies** in T20 cricket. The purpose includes:
1. **Performance Evaluation** - Assessing player contributions to the match outcome.
2. **Match Strategy Analysis** - Understanding team tactics in different game phases.
3. **Team & Player Optimization** - Identifying strengths and weaknesses for better selection and training.
4. **Game Prediction & Decision Making** - Using past trends to anticipate match outcomes and improve decision-making.

## 📂 Dataset Description
The dataset contains ball-by-ball records of a T20 match with columns such as:
- **over**: The over number (0-19).
- **ballnumber**: Ball number in the over.
- **batter**: Name of the batter facing the delivery.
- **bowler**: Name of the bowler delivering the ball.
- **runs_batter**: Runs scored by the batter on that ball.
- **runs_extras**: Extra runs awarded (wide, no-ball, etc.).
- **runs_total**: Total runs (batter + extras).
- **wickets_0_player_out**: Name of the dismissed player (if any).
- **wickets_0_kind**: Type of dismissal (bowled, caught, etc.).
- **team**: The batting team on that ball.

## Key Insights
### 1️. **Batting Insights**
- **SA Yadav, S Dube, and SR Taylor** were the top scorers.
- Most deliveries resulted in **0 or 1 run**, with sixes being rare.
- **Death overs (15-19) had the highest scoring rate**, while the powerplay (0-6) was more cautious.

### 2️. **Bowling Performance**
- **JJ Bumrah and Mohammed Siraj had the best economy rates**, restricting runs effectively.
- **Arshdeep Singh and Jasdeep Singh** were among the most expensive bowlers in terms of runs conceded.

### 3️. **Over-wise Trends**
- **Powerplay overs (0-6):** Lower run rate, cautious batting.
- **Middle overs (7-14):** Moderate scoring, frequent wicket losses.
- **Death overs (15-19):** Higher run rate, aggressive batting.

### 4. **Wicket Analysis**
- Wickets were evenly distributed across the innings.
- Significant dismissals occurred in **middle and death overs**.

## Tools & Libraries Used
- **Python** for data analysis
- **Pandas & NumPy** for data processing
- **Matplotlib & Seaborn** for visualization

## Future Enhancements
- **Feature Engineering**: Incorporate advanced metrics like run rate per over.
- **Player-Specific Analysis**: Detailed performance insights per player.
- **Comparative Analysis**: Compare different matches for trend analysis.

##  Conclusion
This project provides deep insights into T20 cricket match trends using data analytics. The findings can be valuable for players, coaches, and analysts in understanding game strategies and player effectiveness.
