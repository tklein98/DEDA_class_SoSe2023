## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **DEDA_SoSe23_HU_NBA_SHAP_Data_Sourcing_NBA_Games_descriptive** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml


Name of Quantlet: data_sourcing

Published in: 'DEDA Class SS23'

Description: 'Sourcing of the necessary player information from Sqlite database on play by play data from NBA games'

Keywords: 'SQL, Data Sourcing, Raw Data, NBA, play by play data'

Author: 'Oliver KLatt Tustanowski, Jannic Horst, Tobias Klein'

Datafile: 'nba.sqlite, lakers_rosters.csv'

Output: 'lakers_season_18_19_absolute.csv file containing absolute stats for each player for each game.
         CAUTION: Due to the size of the sqlite database, we are working here with a reduced dataset 
         that does not contain all games of the 18_19 season. In the further steps however, 
         we will be working with the complete dataset for the 18_19 season. 
         The full sqlite database (2.3GB) can be found here: https://www.kaggle.com/datasets/wyattowalsh/basketball'