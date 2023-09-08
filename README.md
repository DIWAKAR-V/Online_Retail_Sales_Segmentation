**Online_Retail_Customer_Segmentation:** 

Unsupervised ML Clustering Analysis:

The need of customer segmentation:
The differences in customers' behaviour, demographics, geographies, etc. help in classifying them in groups. Learning about different groups in the customer can help with following:

Target Marketing Client understanding Optimal product placement Searching for new customers Revenue growth

Recency-Frequency-Monetary (RFM) model to determine customer value:
The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase? Frequency – How often do they purchase? Monetary Value – How much do they spend? A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

Segmentation with K-means clustering:
Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton. Then, the unsupervised classification technique, K-means clustering algorithm, is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm. The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.

Conclusion:

1.Initiating the task, we found that our raw data contains about 25% missing 
  values and we also found some duplicate values. We performed data cleaning to get rid of these values and also cancelled orders.

2.We derived important business insights based on products, time and location.

3.We also performed feature engineering. This included deriving new date and time features and getting a new feature giving the total amount of transaction using price and quantity of order.

4.We then performed RFM analysis of the transaction data. This helped us gain importance metrics to build models for customer segmentation.

5.Model building included Segmentation Using RFM Scores(Heuristic Model) which gave us 4 major segments.

Further we used the Machine Learning Models giving us the results as follows:

##1.K-Means Clustering:

###**Elbow Method - 4 Clusters*

###***Silhouette Score - 2 Clusters*

##2.DB-Scan :- 4 Clusters*

Based on the companies goals, we can use these models and their obtained clusters to build business strategies, marketting campaigns, etc. to target, insentivise and attract customer base.
