# Customer-Campaign-Segmentation-Analysis

This project deals with customer data related to a supermarket which spans for 2 years. We can use the data to analyze trends and infer how people interact with campaigns conducted by supermarket. 

I created additional features which help in dimensionality reduction where unnecessary columns can be deleted. There are NA values too in the dataset in couple of columns which have been replaced with their mean. 

I performed EDA to understand the customer spending for 2 years monthly and also clustered manually into 6 campagins by default as the plots depict different picture every time when there is a campaign.

To understand the data better and cluster customers based on the campaign, I built a K-means clustering model since the data is not labelled already. Model had clustered the data into much lesser number of clusters than the actual count we initialized in the beginning. The optimal value of k is retreived from Elbow method with WCSS.
