# Predicting the Modern Adjusted Three Point Percentages of Past NBA Players

This project aims to predict the 3-Point shooting percentages of historic NBA players when adjusted for the modern era of the NBA. This project uses data from every player in every season since 1959, which is well before the inclusion of the 3-point line in 1979. By analyzing the recent 15 years of the NBA, we can create an AI regression model where a players season 3P% can be predicted. The model chosen for this Random Forest Regression and features are selected through a process of exploratory data analysis.

This project can serve as a reference point for possible debates or speculation when talking about the legacy of NBA players. Sports in general (especially the NBA) change a lot from generation to generation. Whether this be by rule changes, interest, player health etc. It is important to have tools such as this project to analyze how the sport changes over time to keep meaningful accounts of the past and to plan for the future.

Dataset: The dataset I have chosen is the NBA Basketball Season Stats dataset from Kaggle (https://www.kaggle.com/datasets/blitzapurv/nba-players-data-1950-to-2021?select=seasons_stats.csv).
This dataset includes the statistics of every player in each of their seasons from 1950-2022. For example, an entry would include the year (1950-2022), the player’s name, and about 50 statistics that player had in the specified year. 

Random Forest Regression Model is used primarily in this project. We look at metrics such as the Mean Absolute Error and Mean Squared Error. We get a good MAE of around .02. We also look at this dataset with KNN with K values from 1-20. We also use other EDA to help shape this data.

We found that the Random Forest Regression Model was able to attain a MAE of about 0.02. This means that the average error was only 2% from the real 3P%. We also determined the predicted 3P% of several past NBA players such as Kareem Abdul-Jabbar and Michael Jordan.



<img width="536" alt="Screen Shot 2022-12-16 at 7 37 33 PM" src="https://user-images.githubusercontent.com/102937958/208213476-6bb1b120-9a7c-415e-a875-c8f63d806261.png">
