# Capstone-Project
Anomaly detection is identifying data points in data that don’t fit the normal patterns. It can be useful to solve many problems including fraud detection, medical diagnosis, etc. 

This is important to detect fraud and various attacks. For example, if large sums of money are spent one after another within one day and it is not your typical behavior, a bank can block your card and notify you immediately.

The goal of the project is to develop and compare regression models, eventually selecting the best model for anomaly detection. First, I trained the models on the original data, then trained the models on the transformed data. Finally, we compared results to give the best model recommendation.

After trying a few times, I realized that my dataset, which I chose before, was not giving me good results as expected. So, I have taken data from known source, Kaggle.

Before started exploratory data analysis, I started with inspecting the data and got all the statistical information for the numeric columns and got an idea about their distribution and outliers. Then I checked and analyzed for the null values. Theoretically, 25 to 30% is the maximum missing values are allowed, beyond which we might want to drop the variable from analysis. Almost 60 to 70% of the project is a data preparation. I explored and proposed various data mining and Machine Learning/Artificial Intelligence approaches. I also reduced the features form 400+ to 140+. Mainly I compared two ML models namely Logistic regression and Decision tree. We can explore a few more boosting methods such as CatBoost and XGBosst to get the better results in future.

Sometimes removing outliers tend to improve the model meanwhile sometimes outliers may give a very different approach to your analysis.

The Modeling phase is about train and test the model to select the best performed model. In this phase, a machine learning regression models have been trained, developed, and selected to answer the business problems. We can detect anomalies using supervised, unsupervised, and semi-supervised methods.

After conducting an exploratory data analysis and identifying the importance of the model features. Logistic regression presented the highest ROC-AUC score. It performed better than the base model for producing high recall score. However, the precision of this model was poor leading to the decrease in accuracy.

