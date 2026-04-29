# IPL-Cricket-Performance-Analytics


## Overview
End-to-end data analysis of [200,000+] IPL ball-by-ball delivery records and [900+] matches across [16] seasons. Built to uncover strategic patterns in batting, bowling, team performance, and venue effects using Python.

## Objectives
- Identify top-performing players by consistency, not just aggregate stats
- Quantify toss and venue impact on match outcomes
- Track evolution of team strategy across seasons
- Build a reproducible, thesis-grade analytical pipeline

## Dataset
- Source: Kaggle — IPL Complete Dataset
- Files: matches.csv ([900+] rows) · deliveries.csv ([200,000+] rows)
- Coverage: IPL Season 1 ([2008]) to Season [16] ([2023])

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy · Jupyter Notebook

## Key Findings
1. Teams fielding first win [X]% of matches league-wide
2. Death-over scoring rates grew [Z]% from 2008 to 2023
3. Only [N] players qualify as both high-average AND high-consistency (top-right quadrant)
4. Toss advantage varies by venue — strongest at [Venue A] ([Y]% win rate for toss winner)
5. All-rounders dominate the top-10 impact score rankings — [N] of top 10 are all-rounders

## Project Structure
ipl_analysis/
├── data/ # Raw CSVs
├── IP Analytics/ # Jupyter notebooks

## How to Run
1. Clone the repo
2. pip install pandas numpy matplotlib seaborn scipy jupyterlab
3. Open notebooks/IPL Analytics.ipynb
