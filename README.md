# HACKATHON-With-a-COVID-19
Covid India Predictions Aug'20


# We used a combination of 3 methodologies to publish the final predictions:

1) FB Prophet Models
2) Xgboost Models
3) Trendlines

Each methodology was tried for every state for different training horizons, validated for 21 days & then the model/weighted combination of models' predictions giving the best metric(RMSE) was finally chosen to produce final set of predictions.

# The Following are the code files we used:

1) Code_Prophet_Multistep_pred.ipynb -- Using Prophet Models to Produce 21 days of predictions (MultiStep Forecasting).
2) Code_Prophet_OneStep_pred.ipynb -- Using Prophet Models to Produce a single day prediction, then include that prediciton into next training data and predict next day and so on.
3) Code_XgBoost_Covid_One Func Model.ipynb  -- XgBoost Models for 21 days of forecasting. 21 Models are created for each state doing 21 days of predictions.


