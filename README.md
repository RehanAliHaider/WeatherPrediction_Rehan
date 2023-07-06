# WeatherPrediction_Rehan
Data Science Project 
Project Report: Predicting Apparent Temperature using Weather Data
1. Introduction
The objective of this project is to build a predictive model that can accurately predict the apparent 
temperature based on weather data, specifically the temperature and humidity. The model aims to 
provide insights into the relationship between these weather features and the perceived 
temperature.
2. Dataset
The dataset used in this project is the "Szeged Weather" dataset obtained from Kaggle. It contains 
historical weather data including features such as date, summary, precipitation type, temperature, 
apparent temperature, humidity, wind speed, wind bearing, visibility, loud cover, pressure, and 
daily summary. The dataset consists of 96,453 records.
3. Data Exploration and Preprocessing
Explored the dataset by examining its structure, missing values, and statistical summary.
Handled missing values in the 'Precip Type' column by filling them with 'No Data'.
Performed one-hot encoding on the 'Precip Type' column to convert categorical data into numerical 
representation.
4. Data Analysis and Visualization
Plotted a scatter plot to analyze the relationship between temperature and humidity.
5. Feature Engineering
Created a new feature called 'Temp Difference' by subtracting the temperature from the apparent 
temperature.
6. Model Training and Evaluation
Split the dataset into training and testing sets.
Utilized the Linear Regression algorithm to train a model using the temperature and humidity 
features.
Evaluated the model's performance using the mean squared error (MSE) metric.
7. Model Tuning and Improvement
Implemented a feature selection technique to identify the most influential features for model 
training.
Re-evaluated the model's performance using the selected features.
8. Results and Conclusion
The final model achieved the following evaluation metrics:
Mean Squared Error: 1.0597
Root Mean Squared Error: 1.0294
Mean Absolute Error: 0.5551
R-squared: 0.9908
The model demonstrated a good performance in predicting the apparent temperature based on the 
temperature and humidity features.
Further analysis and improvement can be done by exploring additional features or trying different 
models or algorithms.
9. Conclusion
In this project, we successfully built a predictive model to forecast the apparent temperature using 
weather data. The model showed high accuracy and performance, with low errors and a high Rsquared value. The temperature and humidity features proved to be influential in predicting the 
apparent temperature. However, further exploration and refinement can be done to enhance the 
model's performance, such as incorporating additional features or experimenting with different 
algorithms.
Overall, this project contributes to understanding the relationship between weather factors and 
human perception of temperature. It can be valuable in various domains, including weather 
forecasting, outdoor planning, and climate analysis.
10. References
Kaggle: Szeged Weather

