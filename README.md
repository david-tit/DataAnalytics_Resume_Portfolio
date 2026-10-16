# Data Analytics Portfolio

Six Python data analysis projects from my coursework, covering exploratory analysis, statistics, clustering, simulation, and visualization. Each folder has a `main.py` (code only) and a Jupyter notebook (interactive version) plus its dataset.

**About this repo's history:** this is a cleaned-up, reorganized copy of my original DataAnalytics coursework repository (renamed folders, local dataset paths, added READMEs). That is why it has only a couple of commits. The original working history lives in my full coursework repo.

## Projects

| # | Project | Data | Key numbers |
|---|---------|------|-------------|
| 1 | [Climate Data Analysis](01_Climate_Data_Analysis/) | Monthly temperature and precipitation, 1895-2022 (128 years) | Average annual temperature rose from about 39.1F (1895-1924) to about 42.0F (1993-2022); linear trend of roughly 2.7F per century. Average annual precipitation rose from about 40.9 to 45.7 inches over the same spans |
| 2 | [Seattle Housing](02_Seattle_Housing_Analysis/) | 4,600 home sales | Living area has the strongest correlation with price (r = 0.43); the 33 waterfront homes had a median price of about $988,500 vs. $460,000 for the rest; 49 listings with a price of $0 needed cleaning |
| 3 | [Driver Behavior Clustering](03_Driver_Behavior_Clustering/) | 4,000 drivers, distance and speeding features | Unsupervised clustering to look for distinct driving profiles without labels |
| 4 | [Baseball Salaries and Wins](04_Baseball_Salary_Analysis/) | 587 team seasons, 1986-2025 | Team salary and win percentage are only weakly correlated (r = 0.22) |
| 5 | [Monte Carlo Stock Simulation](05_Monte_Carlo_Stock_Simulation/) | 97 years of S&P 500 returns, 1928-2024 | Historical mean return of about 11.8% per year with a standard deviation of about 19.5%; 26 of 97 years were negative |
| 6 | [Boston Crime Visualization](06_Boston_Crime_Analysis/) | 327,820 incidents, 2015-2018 | Most common incident type is motor vehicle accident response (about 11.6%); incidents peak at 5 PM; most incidents are in district B2 |

## Shared utilities

`data_analytics_lib.py` has reusable statistics and plotting functions used across the projects.

## Run it

```
pip install -r requirements.txt
jupyter notebook
```

