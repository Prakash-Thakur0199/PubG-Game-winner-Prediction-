# PubG-Game-winner-Prediction-
Battle Royale-style video games have taken the world by storm. 100 players are dropped onto an island empty-handed and must explore, scavenge, and eliminate other players until only one is left standing, all while the play zone continues to shrink.
PlayerUnknown's BattleGrounds (PUBG) has enjoyed massive popularity. With over 50 million copies sold, it's the fifth best selling game of all time, and has millions of active monthly players.
What's the best strategy to win in PUBG? Should you sit in one spot and hide your way into victory, or do you need to be the top shot? Let's let the data do the talking!
the goal is to predict the winning team or player based on various game attributes such as the number of kills, headshots, longest kills, weapon change, etc.

Approach --
Data Collection: The first step involved collecting the dataset for PUBG game from Kaggle https://www.kaggle.com/competitions/pubg-finish-placement-prediction/data.

Data Wrangling: The dataset was then subjected to data wrangling techniques like cleaning, transformation, and integration to make it suitable for analysis.

Exploratory Data Analysis: Exploratory Data Analysis (EDA) was carried out to identify patterns and relationships between different variables in the dataset.

Feature Engineering: New features were created based on the existing data to improve the accuracy of the prediction model.

Model Selection: After feature engineering, various machine learning models were evaluated for the prediction task, and CatBoost was selected as the best algorithm for the given problem.

Model Training: The selected CatBoost algorithm was trained on the cleaned and transformed dataset.

Model Evaluation: The trained model was then evaluated using appropriate evaluation metrics like accuracy, precision, recall, and F1-score to ensure that it is performing well on unseen data.

Hyperparameter Tuning: The model hyperparameters were optimized to further improve the performance of the model.
