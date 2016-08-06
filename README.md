# Machine_learning_project
# Predicting Citi Bike Station Occupany Status

# Problem
To predict the occupancy status of a Citi Bike station within the next one hour using machine learning algorithms
# Objectives
Understand ridership patterns in the context of network inbalances
Influence of factors like time of the day, day of the week
Convert existing scenario into a prediction problem
Performance comparisons of machine learning algorithms

# Methods Used
Computing target variables
Empty Model: if occupancy status == 0, empty else not-empty
Full Model: if occupancy status == 1, full else not-full
Classification Approach
Random Forests, Naïve Bayes, Support Vector Machines, Decision Trees, k-Nearest Neighbors
Train Test Split: 67% and 33% respectively
k-fold cross validation for parameter tuning
Evaluation Metrics: Accuracy, Recall

# Results :
Occupancy Status Analysis
Bike stations with higher empty rates compared to full rates
Clustering Analysis
Distinct groups based on occupancy status metric
Classification Results
Good performance for Empty, not so for Full
Random Forest Classifier , tuned for n_estimators = 20
kNN, Decision Trees, Naïve Bayes gave similar performance

# limitation :
Non-inclusion of Jan-Mar 2016 data
Missing data for some hourly intervals
10 minute intervals would be more accurate
Use of data on MTA Subway turnstiles, sports events





