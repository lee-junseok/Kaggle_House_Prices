# Kaggle_House_Prices

Work for the Kaggle Competition "House Prices: Advanced Regression Techniques"

Competition overview:

'''

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

- Practice Skills
Creative feature engineering 
Advanced regression techniques like random forest and gradient boosting

- Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

'''

Files:


- requirements.txt contains packages used this work.

- EDA contains data exploring and feature engineering ideas with plots.

- Modeling contains data preprocessing, feature engineering, modeling and prediction.

The baseline model with simple data preprocessing and modeling with RandomForest Regressor gives an root-mean-sqaured-logarithmic-error ~0.15. My work with Lightgbm improved it to ~0.02.
