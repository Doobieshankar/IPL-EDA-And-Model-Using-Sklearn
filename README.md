# 🏏 IPL Data Analysis Project (Python | Pandas | Visualization)

## 📌 Project Overview

This project focuses on **exploratory data analysis (EDA)** of IPL (Indian Premier League) ball-by-ball cricket data using Python. The dataset contains around **10,000+ records**, providing detailed insights into matches, players, teams, and performance metrics.

The goal of this project is to analyze and visualize cricket data to uncover meaningful patterns and insights **without using machine learning (for now)**.  
➡️ Future updates will include **ML model creation and prediction systems**.

---

## 📂 Dataset Description

The dataset includes the following types of information:

- **Match Details**: match_id, date, season, venue, city
- **Teams**: batting_team, bowling_team
- **Players**: batter, bowler, non_striker
- **Performance Metrics**: runs_batter, runs_total, wickets
- **Match Outcome**: match_won_by, player_of_match
- **Game Context**: over, ball, innings, toss_decision

---

## ⚙️ Technologies Used

- 🐍 Python
- 📊 Pandas
- 📈 Matplotlib
- 🎨 Seaborn
- 📓 Jupyter Notebook / VS Code

---

## 🧹 Data Preprocessing

- Converted date columns to datetime format
- Handled missing values in categorical fields
- Removed duplicate records
- Created new features:
  - Match phases (Powerplay, Middle, Death)
  - Strike rate (batters)
  - Economy rate (bowlers)
  - Run rate (teams)

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Team Analysis

- Total runs scored by each team
- Match-winning trends

### 🔹 Player Analysis

- Top batters by runs
- Strike rate comparison
- Top bowlers by wickets
- Economy rate analysis

### 🔹 Match Insights

- Toss decision impact
- Match outcome distribution
- Player of the match analysis

### 🔹 Advanced Analysis

- Runs by match phases
- Boundary distribution (4s & 6s)
- Wicket type distribution
- Venue-based performance
- Runs progression per match

---

## 📈 Visualizations

- Bar charts (team/player performance)
- Line charts (runs progression)
- Heatmaps (correlation, over-wise runs)
- Histograms (run distribution)
- Count plots (categorical insights)

---

## 🔍 Key Insights

- Batting-heavy teams dominate T20 format
- Death overs contribute the highest runs
- Top players significantly influence match results
- Toss is not a guaranteed advantage
- Venue conditions impact scoring patterns

---

## 🚀 Future Enhancements

This project will be extended with:

- 🤖 Machine Learning Models:
  - Match winner prediction
  - Player performance prediction

- 📊 Dashboard Development:
  - Power BI / Tableau dashboards
  - Interactive Streamlit web application

- ⚡ Big Data Optimization:
  - Handling larger datasets efficiently

---

## 📁 Project Structure

- root_folder
  - ipl_data_analysis.ipynb
  - IPL.csv (get this csv from Kaggle "https://www.kaggle.com/datasets/chaitu20/ipl-dataset2008-2025")

---
