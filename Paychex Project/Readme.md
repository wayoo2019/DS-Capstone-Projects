In this project, we identify the external activities that have significant impacts on Paychex’s revenue to build prediction models that will forecast Paychex's future monthly revenue. In the end, we choose the best performed model by using predefined performance metrics and we deliver constructive suggestions for Paychex to increase their future revenue. In terms of methodology, we perform exploratory data analysis, preliminary feature selection, and feature engineering to extract correlated features. Then, we input correlated features into our prediction models starting with SARIMA, build up to hybrid, GAM, and deep learning model --- LSTM. To produce better results, we optimize each model with recursive feature engineering and hyperparameter tuning. We choose our best model based on the lowest MAPE and the best model we get is the FB-Prophet with a MAPE of 4.9% which can be interpreted as highly accurate based on the 5% threshold.

1. Final Presentation.pdf
2. Final_Report_Paychex2.pdf
3. PX_0_yuan.ipynb: This notebook includes Feature Engineering, Time Series decomposition, SARIMA model, and FB-Prophet model initial tuning.
4. PX_v1_Yuan.ipynb: This notebook includes: data visualization, SARIMA model, ThymeBoost model, and FB-Prophet model

