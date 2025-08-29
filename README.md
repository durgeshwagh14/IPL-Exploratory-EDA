# 🏏 IPL Exploratory Data Analysis (EDA)

This project explores the **Indian Premier League (IPL)** dataset to analyze teams, players, and match outcomes using Python.

## 📊 Key Insights
- Team performance trends across seasons  
- Top batsmen & bowlers statistics  
- Toss decisions & match-winning factors  
- Venue-wise analysis and patterns  

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly

## 📊 Data Sources
The project is based on **two official IPL datasets**, merged using the `id` column to create a comprehensive DataFrame:

1. **Matches Dataset (`matches_df.csv`)** – Match-level information  
2. **Balls Dataset (`balls_df.csv`)** – Ball-by-ball details  


## 🧾 Dataset Information

### 1. Matches Dataset
Contains details of each IPL match.  
| Column | Description |
|--------|-------------|
| id | Unique match identifier (Primary Key) |
| city | City where the match was played |
| date | Match date |
| player_of_match | Awarded "Man of the Match" |
| venue | Stadium name |
| team1, team2 | Teams competing |
| toss_winner | Toss-winning team |
| toss_decision | Bat/Field decision |
| winner | Match-winning team |
| result | Win type (runs/wickets/tie) |
| result_margin | Margin of victory |
| eliminator | Indicates eliminator (Y/N) |
| method | DLS applied (if any) |
| umpire1, umpire2 | Match umpires |


### 2. balls Dataset
Captures every delivery of each match.  
| Column | Description |
|--------|-------------|
| id | Match ID (Foreign Key) |
| inning | Inning number (1/2) |
| over, ball | Over & ball count |
| batsman, non_striker | Batting players |
| bowler | Bowler’s name |
| batsman_runs, extra_runs, total_runs | Run details |
| is_wicket | Wicket indicator (0/1) |
| dismissal_kind | How the batsman was out |
| player_dismissed | Name of dismissed batsman |
| fielder | Fielder involved in dismissal |
| extras_type | Type of extra (wide, no-ball, etc.) |
| batting_team, bowling_team | Teams in play |


## 🚀 Steps
1. Data cleaning & preprocessing  
2. Exploratory data analysis (EDA)  
3. Visualizations for insights

## ▶️ How to Run This Project
To explore this analysis on your local system or Google Colab:

1. Clone or download the repository.  
2. Ensure required libraries are installed:  
   ```bash
   pip install pandas matplotlib seaborn


## 📌 Outcome
A data-driven understanding of IPL with **interactive charts & insights** that help analyze team strategies, player impact, and match trends.
