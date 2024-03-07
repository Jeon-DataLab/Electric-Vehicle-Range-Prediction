## Electric Vehicle Range Prediction

**Project Overview**
This project leverages the Electric Vehicle Population Data from the US Department of Licensing to predict the electric range of vehicles. The data captures an array of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered in Washington State.

**Project Goal**
The goal is to construct a regression model to predict the electric range of EVs accurately, aiding consumers in making informed decisions and providing the industry with competitive analysis and trends.

**Dataset**
With 166,800 entries across 17 columns, the dataset was created on November 10, 2020, and last updated on January 19, 2024.

**Methodology**
The process encompassed data preprocessing, exploratory analysis, and implementing various regression techniques to identify key factors that impact the electric range of EVs.

**Results and Insights**
Three models were evaluated:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

**Model Performance**
-The Linear Regression model performed poorly, with an MSE (Mean Squared Error) of approximately 9.35 × 10^21 and an R^2 score of about −1.07 × 10^18, indicating that the model was not suitable for this dataset.
- The Random Forest Regressor showed excellent perormance with an MSE of 23.52 and an R^2 score of 0.9973, suggesting the model was able to explain 99.73% of the variance in the electric range of the vehicles.
- The Gradient Boosting Regressor also performed well, with an MSE of 67.79 and an R^2 score of 0.9922, explaining 99.22% of the variance.

The models were further analyzed to determine feature importance, revealing that 'Model Year' and the 'Electric Vehicle Type' are significant predictors of a vehicle's electric range.

**Feature Importance**
The top feature importances from the Random Forest and Gradient Boosting models are as follows:

- Model Year
- Electric Vehicle Type
- Specific Models and Makes (e.g., TESLA Model 3, NISSAN LEAF)
These insights indicate that newer vehicle models and the specific type of EV (BEV or PHEV) play a critical role in determining the electric range.

**Conclusions**
The analysis has provided a clear understanding of the features that influence electric range most significantly. Such models can guide potential EV buyers and help manufacturers focus on the factors that matter most in improving the range of their vehicles.
