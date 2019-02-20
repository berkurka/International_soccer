# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Soccer Clustering:

### Overview

Clustered international countries soccer teams using past results as features.

Notebooks:

1. [DataScraping.ipynb](https://github.com/berkurka/Reddit-Classifier/blob/master/Notebooks/01%20DataScraping.ipynb)
     Scraping data from sub reddit Api convert into a pandas data frame and creates csv files.

### Methods
 - Statistic data description and feature engineering using Pandas and Numpy, libraries from Python.
 - Sklearn K-Means Clustering algorithm.

### Results
 - Split the data into 4 different clusters.
 - Cluster 0: Highest winning teams throughout history with lots of world cup games.
 - Cluster 1: Teams that have achieved success in some world cups but have not done it consistently. Medium number world cup games.
 - Cluster 2: Teams that have gone to some world cup tournaments but had not achieved significant results.
 - Cluster 3: Teams that have been to 1 or 2 world cups and had bad performance.
### Software Used
- Jupyter notebook
- Python 3.6
- Tableau

### Data

#### Data source

[International Football Kaggle](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017/home)

#### Feature dictionary
|Feature|Type|Description|
|---|---|---|
|team|String|Country name|
|world_cup_games|integer|Number of Fifa World Cup games|
|world_cup_wins|integer|Number of Fifa World Cup wins|
|world_cup_ties|integer|Number of Fifa World Cup ties|
|world_cup_losses|integer|Number of Fifa World Cup losses|
|world_cup_win_pct|float|World Cup Win Percentage|
|world_cup_tie_pct|float|World Cup Tie Percentage|
|world_cup_loss_pct|float|World Cup Loss Percentage|
