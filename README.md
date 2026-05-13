# NBA Championship Probability Model

## Overview
This project develops a predictive model to estimate each NBA team's probability of winning a championship for the 2026 season based on regular season performance metrics.

The model uses:
- Multi-season team data
- Feature engineering (efficiency metrics + interactions)
- LASSO-regularized logistic regression

The goal is to produce probabilistic predictions rather than binary classifications, allowing for a more nuanced evaluation of team strength.

Although the project is focused on making predictions for the 2026 season (as of May 2026), the code also looks into predictions for previous seasons and could easily be modified for future seasons as well. 

In order to do so:
  - The TRAIN_SEASONS variable must be changed to look at the desired range of seasonal data for the model to look at
  - The PREDICT_SEASON variable must look at the desired season to predict.  
  - The CHAMPIONS variable must include all championship teams with the desired training years
  - Comments, documentation, graph titles would need to be changed to include the right seasons
