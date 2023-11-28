# NY-Taxi-Traffic
A comprehensive approach to analyzing New York City taxi trip data using a unsupervised learning methods.

This project demonstrates a comprehensive approach to analyzing New York City taxi trip data using both Pandas/scikit-learn and Apache Spark frameworks. It encompasses five distinct exercises, each addressing a unique aspect of taxi trip data analysis and visualization, and showcases the ability to handle large datasets and implement machine learning algorithms effectively.

Exercise 1: Identifying New Bus Routes

Aim: To suggest potential new bus routes by identifying the most frequented taxi routes above a certain distance threshold.
Approach: Grid-based analysis using both Spark and Pandas to group trip data, filtering out routes below the set distance threshold, and identifying the most common routes.
Exercise 2: Tip Prediction

Aim: To predict whether a taxi trip will include a tip.
Approach: Binary classification using RandomForestClassifier in Pandas, focusing on features like payment type, distance, and time of the trip.
Exercise 3: Optimal Taxi Positioning

Aim: To aid taxi drivers in finding the best areas for picking up passengers at different times and days.
Approach: Analysis of pickup locations and times using Pandas, generating a heatmap to visualize high-demand areas.
Exercise 4: Taxi Rank Location Optimization

Aim: To determine optimal locations for taxi ranks to minimize passenger travel distance to these ranks.
Approach: Clustering analysis with KMeans in Spark, constrained to a specified geographical area of NYC, and visualized through a heatmap.
Exercise 5: Community Detection in NYC

Aim: To identify closely-knit communities within NYC based on taxi trip data.
Approach: Implementation of a label propagation algorithm in Spark's GraphFrames, visualizing the communities as clusters in a scatter plot.
Technologies Used:

Pandas and scikit-learn for data manipulation and machine learning in Python.
Apache Spark for handling large-scale data processing.
Spark MLlib and GraphFrames for machine learning and graph analysis in Spark.
Key Learnings:

Effective handling and analysis of large datasets.
Implementation of machine learning algorithms for real-world data.
Data visualization techniques to represent complex data insights.
Comparative analysis of Pandas/scikit-learn and Spark for different data processing needs.
