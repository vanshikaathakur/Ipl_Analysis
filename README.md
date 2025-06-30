🏏 IPL Analysis (2008–2020)
A comprehensive ball-by-ball and match-level analysis of the Indian Premier League (IPL) using Python, Pandas, and Matplotlib.

📊 Overview
This project performs exploratory data analysis (EDA) on two key IPL datasets to uncover insights into match dynamics, player performances, and game trends.

📂 Datasets
Analysis is based on two interconnected CSV files sourced from [Kaggle’s IPL Complete Dataset (2008–2020)]:

matches.csv
Contains match-level metadata such as match ID, season, teams, toss results, winners, venues, and Player of the Match 


deliveries.csv
Provides ball-by-ball details including runs, extras, batsman, bowler, dismissal type, and over number 


🛠️ Tech Stack
Python (3.x)

Pandas – data manipulation

Matplotlib/Seaborn – visualizations

NumPy – numerical operations

Run it with:
pip install pandas numpy matplotlib seaborn

🔍 Key Analysis Components
1.Data Cleaning & Preparation
• Handle missing values (e.g., dismissal_kind)
• Standardize naming conventions (teams, venues, seasons)

2.Descriptive Statistics & Aggregations
• Runs per over, total runs, extras
• Dismissal type frequencies (dismissal_kind)
• Team-wise toss decisions and win percentages
• Player-level summaries (e.g., top scorers, wicket-takers)

3.Visual Analytics
• Pie charts for dismissal types
• Over-wise run distribution histograms
• Bar charts for top performers
• Trend lines for seasonal performance

4.Player & Match Insights
• Most common dismissal modes for players
• Key players’ impact by match and season
• Toss decision effect on match outcomes

📁 Project Structure
.
├── data/
│   ├── matches.csv
│   └── deliveries.csv
├── notebooks/
│   └── ipl_analysis.ipynb       # EDA in Jupyter
├── scripts/
│   └── ipl_analysis.py         # Python script for analyses
├── README.md                   # (You are here)
└── visuals/                    # Saved charts & plots

🧭 Usage
1.Clone the repo:
git clone https://github.com/vanshikaathakur/Ipl_Analysis.git
cd Ipl_Analysis
2.Install dependencies:
pip install pandas matplotlib seaborn numpy
3.Run the notebook or script:
jupyter notebook notebooks/ipl_analysis.ipynb

or python scripts/ipl_analysis.py

💡 Insights Uncovered (examples)
Dismissal Trends: Count and visualize how batsmen get out (caught, bowled, LBW, etc.).

Scoring Patterns: Runs-per-over heatmaps and distribution across innings.

Decision Analysis: Relationship between toss winners and match winners.

Player Spotlights: SK Raina’s mode of dismissal, Virat Kohli’s strike rate patterns, etc.

🚀 Future Work
🧠 Apply machine learning to predict match outcomes

🏟️ Factor venue and weather conditions in performance analysis

📅 Extend dataset to cover IPL seasons beyond 2020

🔍 Drill down into finer metrics like strike rate by over phase (powerplay, death overs)

Created by Vanshika Thakur
