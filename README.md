# The Price is Right: Predicting Car Value using Machine Learning

## Introduction<br>
As a collaborative team of four car resellers established in 1990, we utilize data collection to gain a deeper understanding of average car sales prices within the market. Our aim in collecting this data is to build accurate car price predictions using advanced Machine Learning models and methodologies. By building a machine learning model, we can provide estimates of car prices to assist buyers, sellers, and dealerships in making informed decisions. 

The data was sourced from [Kaggle](https://www.kaggle.com/datasets/CooperUnion/cardataset).

## Features
**1. Data Cleaning**<br>
The dataset first underwent thorough cleaning to handle any missing values and provide consistency throughout the dataset. Missing values in categorical columns were dropped and for numerical columns, the mean or mode was calculated to replace any missing values. 

**2. Exploratory Data Analysis**<br>
Exploratory Data Analysis was performed to gain an insight into the data. Through this, we were able to determine most popular car brands, average prices for each car brand, and most common features of the cars. Visualizations and statistical summaries were used to understand the distribution and patterns in the data.

**3. Feature Engineering**<br>
Categorical features of the dataset were transformed into numerical values to enhace the predictive power of the model. Given that the features in our data are considered ordinal, a rank needed to be assigned to each value and the weight of each variable needed to be kept. 

**4. Feature Scaling**<br>
Having features with varying degrees of magnitude and range will cause different step sizes for each feature. Therefore, to ensure that gradient descent converges more smoothly and quickly, we need to scale our features so that they share a similar scale. For X_train and X_test, normalization was used to scale the features, whereas standardization was used for y_train and y_test.

**5. Model Building**<br>
Various machine learning algorithms were used to build a model. Random Forest and Gradient Boosting established themselves as best models to achieve a balance between accuracy and robustness in predictive modeling. In order to achieve optimal prediction performance, Random Forest approach was employed for the final mmodel.

**6. Model Evaluation**<br>
The trained model was evaluated using the Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R2 score on both training and validation datasets.

## Key findings and Insights<br>
In our analysis, several key features have emerged as significant predictors of car prices. This features stand out on our model’s predictive performance:
- Make and Model 
- Market Category
- Engine Horsepower
- Engine Cylinders

## Libraries Used
- pandas
- numpy
- seaborn
- matplotlib
- scipy.stats
- sklearn
- plotly
