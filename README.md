# Round Outcome Prediction in Counter-Strike: Global Offensive (CS:GO)

The primary objective of this project is to predict the outcome of rounds in CS:GO, determining whether Terrorists (Ts) or Counter-Terrorists (CTs) emerge victorious. Utilizing a dataset sourced from OpenML, comprising raw data from over 700 matches played between 2019 and 2020, we aim to identify key factors influencing round outcomes.

Dataset Link: [CS:GO Round Outcome Dataset](https://www.openml.org/search?type=data&sort=runs&id=43430&status=active)

Various factors contribute to determining round winners, including:

- Time Left: Reflecting the time remaining in the round, a crucial factor influencing the outcome, especially if the bomb has not been planted by the Ts before time runs out.
- Bomb Planted: A binary variable indicating whether the bomb has been successfully planted.
- CT Health: Total health of all Counter-Terrorist players.
- T Health: Total health of all Terrorist players.
- Number of players alive on each team (CTs and Ts).
- Weapon counts for both CTs and Ts.
  
Given the extensive nature of the dataset, preprocessing is essential to extract relevant features for model training. Once the data is prepared, we will train and evaluate the model's accuracy in predicting round outcomes, striving for reasonable accuracy in distinguishing between Ts and CTs victories. Let's embark on this journey to unveil the intricacies of round outcomes in CS:GO together!
