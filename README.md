# <h1 align="center">🏏 IPL Data Analysis (EDA</h1>

Performing Exploratory Data Analysis (EDA) on IPL match data to uncover patterns in player performance, team strategies, and match outcomes.

# 📑Table of Contents
- <a href="#overview"> Project Overview </a>
- <a href="#business-problem"> Business Problem </a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#key-findings"> Key Findings & Insights </a>
- <a href="#screenshots">Screenshots</a>
- <a href="#author--contact"> Author & Contact </a>
<h2><a class="anchor" id="overview"></a>🔎Project Overview</h2>
This project performs an Exploratory Data Analysis (EDA) on the Indian Premier League (IPL) dataset to uncover insights into player performance, winning strategies, toss impact, seasonal match trends, and hosting venues.
The goal was to transform raw match data into meaningful, actionable insights using Python, pandas, matplotlib.
<h2><a class="anchor" id="business-problem"></a>🎯Business Problem</h2>
The analysis aims to address the following:
•	Identify the most impactful players and teams throughout IPL history.
• Understand whether batting first or fielding first is the more successful match-winning strategy.
•	Examine how toss results influence match outcomes.
•	Highlight patterns across seasons to track how the league evolved over time.
•	Evaluate which cities and venues played the biggest role in hosting IPL matches.
<h2><a class="anchor" id="dataset"></a>📂 Dataset</h2>
•	Source: IPL Matches dataset (CSV format)
•	Size: 1,096 matches × 20 columns 226KB
•	Features: Season, city, venue, teams, toss winner, toss decision, match winner, result type (runs/wickets), winning margin, player of the match
<h2><a class="anchor" id="tools--technologies"></a>🛠 Tools & Technologies</h2>
•	Python
•	Pandas – Data manipulation
•	Matplotlib – Visualizations
•	Jupyter Notebook – Interactive coding and reporting
<h2><a class="anchor" id="data-cleaning--preparation"></a>🧹 Data Cleaning and Preparation</h2>
•	Dropped irrelevant column method (contained only null values).
•	Checked and handled missing values for consistency.
•	Standardized city and venue names for grouping.
•	Converted result margins into numeric formats for comparison.
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>📊 Exploratory Data Analysis (EDA)</h2>
🏅 Player of the Match Analysis
•	AB de Villiers won the most Player of the Match awards (25).
•	Chris Gayle (22) and Rohit Sharma (19) followed closely.
•	Visualizations compared the top 10 performers to show dominance trends.
🪙 Toss Winners and Decisions
•	Mumbai Indians (143 tosses), Kolkata Knight Riders (122), and Chennai Super Kings (122) won the most tosses.
•	Toss wins provided a small edge but did not guarantee match success, showing strategy execution mattered more.
🧠 Winning Strategy: Batting First vs Fielding First
•	498 matches were won by batting first.
•	578 matches were won by fielding first → fielding first emerges as the stronger strategy.
•	Batting first often resulted in larger margins (e.g., 70+ runs), while fielding first wins were tighter.
📈 Distribution of Win Margins
•	Batting-first wins: margins widely spread, with extreme high-run victories.
•	Fielding-first wins: concentrated between 4–6 wickets, showing consistency but limited variability.
🏆 Team Dominance
•	Mumbai Indians (144 wins) lead as the most successful franchise.
•	Chennai Super Kings (138) and Kolkata Knight Riders (131) followed.
•	This aligns with their track record of title wins.
🔥 Season-Level Intensity
•	2013 season had the highest matches (76 games).
•	Other busy seasons: 2012, 2022, 2023.
•	Expansion years and format changes explained higher match counts.
🏟️ City and Venue Hosting Trends
•	Top Cities: Mumbai (173), Kolkata (93), Delhi (90).
•	Top Venues: Eden Gardens, Kolkata (77); Wankhede, Mumbai (73); M. Chinnaswamy, Bangalore (65).
•	Mumbai dominates due to multiple stadiums and frequent playoff/final hosting.
<h2><a class="key-findings" id=""></a>📌 Key Findings & Insights</h2>
•	AB de Villiers is the standout individual performer in IPL history.
•	Mumbai Indians dominated both tosses and matches, showing their consistent strength.
•	Fielding first is the most successful match strategy, though batting first delivers bigger victories when successful.
•	Win margin analysis revealed contrasting patterns: wider run margins vs consistent wicket margins.
•	Hosting trends showed Mumbai, Kolkata, and Delhi as the IPL hubs, with Eden Gardens and Wankhede as iconic venues.
•	The league expanded significantly in match count during certain seasons, reflecting its evolution.


<h2><a class="anchor" id="screenshots"></a>Screenshots</h2>
•	Top 10 Player of the Match performers (bar chart)
•	Toss winner distribution (bar chart)
•	Batting vs Fielding win strategy (bar chart)
•	Win margin histograms (runs vs wickets)
•	Team dominance chart (top 10 winners)
•	Matches per season chart
•	Top cities and venues hosting charts

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>
⦁	Author: Vaibhav Goyal
📧 Email: vg.goyal611@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/vaibhav-goyal-29b70a30/)  
🔗 [Portfolio](https://github.com/vggoyal611)