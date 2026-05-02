# IPL2022-ball-by-ball-analysis
IPL 2022 sports analytics project with phase analysis, clutch metrics, and pressure-based player performance insights using Python.

📌 Overview

This project analyzes ball-by-ball data from IPL 2022 using Python to extract meaningful insights about player performance, match situations, and team outcomes.

The analysis goes beyond basic statistics by incorporating context-aware sports analytics, focusing on how players perform under different match conditions such as phases, pressure, and high-impact situations.

🎯 Objectives
Analyze player and team performance using ball-by-ball data
Evaluate performance across different match phases
Identify impactful players in winning scenarios
Develop custom metrics to measure performance under pressure

🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab

📂 Dataset
IPL 2022 Ball-by-Ball dataset (~17,900+ deliveries)

Features include:
Batter, Bowler
Runs (batsman, extras, total)
Wickets and dismissal types
Teams and match IDs

📈 Basic Analysis
Total runs scored in IPL 2022
Top batsmen by runs
Top bowlers by wickets
Team-wise total runs
Distribution of runs per ball

🔍 Advanced Analysis
🟠 Phase-Based Performance
Divided innings into:
Powerplay (Overs 0–5)
Middle Overs (6–15)
Death Overs (16–20)

Calculated:
Batsman strike rate per phase
Bowler economy rate per phase

🟣 Player Consistency
Measured using:
Average runs per match
Standard deviation
Identified players with consistent performance across matches

🔵 Match Context Analysis
Compared winning vs losing team performance
Identified impact players in winning matches

🔥 Custom Sports Analytics Metrics:

🔴 Finisher Score
Focused on death overs performance (16–20)
Combines:
Total runs
Strike rate
Identifies players who excel at finishing innings

🟣 Clutch Performance Metric
Defined clutch situations as:
Death overs
OR when 5+ wickets have fallen
Measures player ability to perform under high-pressure scenarios

🟡 Pressure Index
Custom metric combining:
Match progression (overs)
Wickets fallen
Quantifies pressure level for each delivery

🔵 Performance Under Pressure
Evaluated players based on:
Strike rate
Pressure index
Identified players who maintain performance in difficult situations

📊 Key Insights
Certain players significantly improve performance in death overs, highlighting finishing ability
Bowlers with low economy in late overs demonstrate strong pressure handling
Consistent players provide stable contributions across matches
High-performing players in winning matches often have strong clutch metrics
Most deliveries result in 0 or 1 run, emphasizing the importance of strike rotation

🎯 Real-World Applications
Helps teams identify reliable finishers and clutch players
Assists in player selection and match strategy
Enables data-driven decision making in high-pressure situations
Demonstrates how raw sports data can be transformed into actionable insights

🚀 How to Run
Upload dataset to Google Colab
Run the notebook step-by-step
Generate insights and visualizations

📌 Conclusion
This project demonstrates how ball-by-ball cricket data can be used to perform advanced sports analytics. By incorporating match context and custom metrics, the analysis moves beyond basic statistics to provide deeper insights into player performance and game dynamics.
