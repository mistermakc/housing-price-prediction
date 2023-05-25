# Housing Price Prediction

This project focuses on predicting housing prices using machine learning techniques. The goal is to develop a model that can accurately estimate the price of a house based on various features.

## Objective

The objective of this project is to create a regression model that can predict housing prices. By analyzing a dataset containing information about different houses, we aim to build a model that can capture the relationships between the input features and the sale prices. This model can then be used to make predictions on new, unseen data, helping potential buyers and sellers make informed decisions.

## Methods Used

The project utilizes various data analysis and machine learning methods, including:

- Data exploration and visualization: We analyze the dataset, identify key variables, and gain insights into the distribution and relationships of the features and the target variable (sale prices). Visualizations such as histograms, box plots, scatter plots, and heatmaps are used to understand the data.

- Data preprocessing: Before training the machine learning models, we perform data cleaning and preparation steps. This includes handling missing values, handling outliers, transforming skewed variables, standardizing numerical features, and encoding categorical variables.

- Feature selection: We select relevant features that have a strong correlation with the target variable and drop irrelevant or highly correlated features. This helps improve the model's performance by focusing on the most informative input features.

- Model training and evaluation: We train several regression models, including Linear Regression, Decision Tree, Random Forest, and Gradient Boosting. Cross-validation is used to assess the models' performance and measure the mean root mean squared error (RMSE) as an evaluation metric.

## Results

The performance of the trained models is as follows:

- Linear Regression:
  - Mean RMSE: 27366.81
  - Standard Deviation: 20273.91

- Decision Tree:
  - Mean RMSE: 0.60
  - Standard Deviation: 0.01

- Random Forest:
  - Mean RMSE: 0.49
  - Standard Deviation: 0.02

- Gradient Boosting:
  - Mean RMSE: 0.47
  - Standard Deviation: 0.02

The results indicate that the Gradient Boosting model performs the best, with the lowest mean RMSE and standard deviation. This suggests that the Gradient Boosting model captures the relationships between the input features and housing prices most accurately among the models tested.

## Conclusion

In conclusion, this project demonstrates the application of machine learning techniques for predicting housing prices. The analysis of the dataset, data preprocessing, feature selection, and training of regression models provide insights into the factors influencing housing prices. The Gradient Boosting model shows the best performance in predicting housing prices. The developed model can be used to estimate housing prices for new data, assisting buyers and sellers in making informed decisions.

