# IPLScorePrediction
This is ML model webapp which predict total score of IPL.

# IPL Toral Score Prediction

This Streamlit webapp enables  predict total runs between teams by using overs, runs, wickets etc.

##### We used Algorithms #####

* Linear Regression
* K-Nearest Neighbor Regressor
* XGBoost Regressor
* RandomForest Regressor
* SVR
* Decision Tree Regressor

## Hyperparamter Optimization ##

Used optuna for paramter-- this package give best combination of hyperparameters that optimizes a given objective function.

##  Information about Dataset ##

The dataset of IPL matches from 2008 to 2022.

Dataset Used: ipl_data.csv

* mid - match id
* date - when matches are played
* venue - place where matches aew played
* bat_team - batting team
* bowl_team - bowling team
* batsman - batsman
* bowler - bowler
* runs - runs scored
* wickets - wickets
* overs - overs - next 3 are based on this
* run_last_5 - runs scored in last 5 overs
* wicket_last_5 - wickets in last 5 overs
* stricker - batsman playing as main 1
* non-striker - batsman playing as runner up - not main 0
* total - total score (target variable)



