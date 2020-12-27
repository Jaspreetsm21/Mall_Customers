# Consumer Behaviour in the Mall: Cluster Analysis 
- Comparing Liverpool's last 10 years of performances with transfer spending each season --> there is evidence to suggest more spending leads to fewer matches been lost but there is no concrete evidence to suggest more spending leads to winning more matches.
- Built a dashboard for Liverpool's performance in the last decade on Streamlit platform which is free and easy to share with stakeholders.
- Optimized K-Means and Hierarchical clustering methods to reach the conclusion of the analysis.
- Built a client facing API and Heroku to view the dashboard on [Streamlit](https://liverpooldashboard.herokuapp.com/).

# Code and Resources Used

**Python Version**: 3.7

**Packages**: pandas, numpy, sklearn, matplotlib, seaborn,json

**Data Resource**: https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python

# [EDA](https://github.com/Jaspreetsm21/Mall_Customers/blob/main/EDA.ipynb)
![](/image/EDA1.PNG)  ![](/image/EDA2.PNG)

![](/image/EDA4.PNG)

![](/image/EDA5.PNG)

![](/image/EDA6.PNG)

### Insigth

# Cluster Analysis
![](/image/Kmean.PNG)

In the plot above the elbow is at k=4. indicating the optimal k for this dataset is 4.

![](image/cluster.PNG)

Cluster 0: Median Age - High Income with Low Spending Score.

Cluster 1: Median Age - High Income High with High Spending Score.

Cluster 2: Young Consumer - Low Income High with High Spending Score

Cluster 3: Older Consumer - Low Income with Low Spending Score

Cluster 1 would be the best segment to target, consumer with Higher Income and Higher spending Score.
