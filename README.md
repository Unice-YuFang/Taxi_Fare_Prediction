# Predicting Taxi Fares with Supervised Machine Learning Models
# Business Problem
In the bustling metropolis, the iconic yellow taxis are more than just a means of transportation; they are a dynamic part of the urban fabric. However, there are many reports and concerns raised by travelers around the world that in some cases, these taxi drivers abusively overcharged the customers, preventing tourists from reaching the full happiness they spent in New York. Besides, taxi companies are facing more challenges in managing the price system and operation processes nowadays. To solve and challenge this unfair practice, our project dives into the heart of this vibrant taxi ecosystem, leveraging machine learning models to find the insights behind the dataset.


# Data Source 
TLC Trip Record Data - Yellow Taxi Trip Records. Direct access [here](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).


# Unsupervised Machine Learning Models
Random Forest Regressor

Gradient Boosting

XGBoost

Decision Tree Regressor

Linear Regression

Lasso

Ridge

![Unknown](https://github.com/Unice-YuFang/Taxi_Fare_Prediction/assets/74975816/4f4c119d-88b5-4847-9893-e8ae6964e6e2)



# Hyper Parameter Search
Grid Search

Halving Search
Random Search
Bayes Search


# Feature Importance
Random Forest Regressor
Gradient Boosting
Decision Tree Regressor


# Result
<img width="255" alt="Screenshot 2023-12-06 at 5 49 51 PM" src="https://github.com/Unice-YuFang/Taxi_Fare_Prediction/assets/74975816/c09a2455-f9d2-4cd7-ba90-8a637b6b969a">
<img width="660" alt="Screenshot 2023-12-06 at 5 51 12 PM" src="https://github.com/Unice-YuFang/Taxi_Fare_Prediction/assets/74975816/f1e2f337-6206-47e5-83b6-c36e2205278f">


# Implications
Based on our results, we think potential implications are significant both for customers and taxi companies. For customers, our data-driven approach enables a trustworthy comparison of taxi fares with benchmark services like Uber and Lyft, ensuring they receive competitive rates. This transparency not only fosters trust but also empowers customers to make informed choices. For taxi companies, the implementation of a new meter system that connects meters to a network and adjusts fares in real-time could revolutionize the industry. Such a system could dynamically respond to various factors like traffic conditions, peak hours, and even weather, thereby optimizing fare structures. This would not only enhance revenue for taxi companies by ensuring more efficient fare adjustments but also improve overall operational efficiency. Ultimately, these advancements could lead to a more balanced and competitive market, benefiting both service providers and consumers.


# Reference
1. [Read parquet format data](https://www.nyc.gov/assets/tlc/downloads/pdf/working_parquet_format.pdf)
2. [Extract time from datatime format](https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.hour.html)
3. [Evaluate a model](https://zhuanlan.zhihu.com/p/624855556)
4. [Install Bayes Search Library - skopt ](https://www.roseindia.net/answers/viewqa/pythonquestions/222078-ModuleNotFoundError-No-module-named-skopt.html)
5. [Hyper parameter tuning methods](https://towardsdatascience.com/bayesian-optimization-for-hyperparameter-tuning-how-and-why-655b0ee0b399)
6. [Overlapping line plots](https://blog.51cto.com/u_16175490/7440021)
7. [Reset index](https://blog.enterprisedna.co/pandas-drop-index/)
