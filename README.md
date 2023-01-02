# Online_Retail_Customer_Segmentation_ML
Project Name - Online Retail Customer Segmentation
Project Type - Unsupervised ML

Contribution - Individual

Name - Vineeta Singh

Email Id - singhvineeta0118@gmail.com

Project Summary-
We first started with knowing more about Problem statement and figuring out the best approach to solve it.

Customer segmentation is the process of dividing your customers into sub-groups based on shared features. Because you use on-site data to optimize advertising off-site, segmentation happens after the fact, unlike customization and targeting.

Because you need to build triggers so that your consumers see the advertisements when they arrive, you need to do your targeting and personalization before they arrive.

In the dataset, we don't have labels. So, the process lies in segmenting customers based on their behavior and then finding insights from that. For e-commerce, this type of information helps a lot in improving advertisements and marking ideas. With customer information and their purchasing behavior, we can cluster those customers in a bucket and then show customized advertisements and also review which platforms are giving us better results.

When a customer makes a purchase, there is some information that is now stored. Such information is given below:

InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country.

While importing Dataset and data inspection we got to know there are no major inconsistencies but we had to deal with missing and duplicate values. Whether to extract the InvoiceDate column at the start or to extract after some visualization was little challenging. So, we created 2 datasets considering both visualizations and at last chose the best path, which was to extract the Datetime feature after some major visualizations.

The sample size of this dataset is 541909. That means initially we had 541909 customer records. And we had 8 features and no label. So, we used all features and did some univariate and multivariate analysis which also included checking and changing the distribution of some variables.

One thing to notice is that we also had Datetime variable. Extracted it and we got many useful variables to form it.

This research work allows us to have an insight into the performance of various predictions and walk through the whole process of clustering.

We investigated the dataset, checked null values, duplicate values. Then getting Dataset ready for exploratory data analysis. Then we did some feature engineering, we extracted the Datetime column for getting some more useful columns. We also created the Total amount as a new variable. Thus, we prepared our data for models.

After that, we created an RFM model (Recency, Frequency, Monetary value). We did a log transformation of R, F, M for better results.

Now comes the model-building part, we used the K-Means clustering algorithm to find the optimal number of clusters that can separate customers based on their purchasing behavior. We then applied the K-Means algorithm with the Silhouette Score Method on RM, FM, RFM simultaneously. Where we got the optimal number of clusters = 2. We then visualized our results with scatterplots. Then moving forward, we applied K-Means with Elbow Method on RM, FM, RFM simultaneously.

Next, we applied DBSCAN on RM, FM, and RFM where we got the optimal number of clusters as 2, 2, 3 simultaneously.

After that, we applied Dendrogram to find the optimal number of clusters and found that the optimal number of clusters is equal to 2.

By applying a different clustering algorithm to our dataset. we get the optimal number of clusters is equal to 2.

GitHub Link-
https://github.com/vineeta0118/Online_Retail_Customer_Segmentation_ML

Thanks
