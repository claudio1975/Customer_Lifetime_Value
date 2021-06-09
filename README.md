# Unsupervised Learning applied to Customer Lifetime Value (CLV) 

![](https://wilsonprintingusa.com/wp-content/uploads/2015/02/Customer-Lifetime-Value-Wilson-Printing.jpg)

The core business of Insurance Companies is to enable individuals and firms to protect themselves against rarely events paying a small premium compared to the eventually damage incurred.

Customer Lifetime Value (CLV) evaluates the value of the customer for the Company, in other words, it’s the Net Present Value of the cash flows ascribed to the relationship with a customer. 

In this work, from the collection of portfolio contracts by one insurance year, will be predicted the Customer Lifetime Value of the last three months of the year, also looking at the effects coming from the use of Unsupervised Learning. 

Unsupervised Learning describes tasks that involves using a model to discover a good internal representation of input data useful for subsequent Supervised Learning. 

In this job Unsupervised Leaning are used to provide a low-dimensional representation of inputs and clustering numerical variables to provide a better portfolio analysis of customers. In both situations, Unsupervised Learning can be used as feature engineering to improve Machine Learning performances.

Exploratory Data Analysis Customer_Lifetime_Value/UL_CLV_EDA_OK2.ipynb

### *Comparison between ML models to evaluate CLV prediction*

![](images/models.png)

### *Comparison between Flat model (baseline) and other models built only with extracted features from dimensionality reduction*

![](images/prediction_dim_reduction_only.png)

### *Comparison between Flat model (baseline) and other augmented models with feature engineering from dimensionality reduction*

![](images/prediction_fe_dim_reduction.png)

### *Comparison between several clustering methods applied to numerical features*

![](images/tsne_kmeans_2D_v2.png)

![](images/tsne_kmeans_3D_v2.png)

![](images/tsne_dbscan_2D.png)

![](images/tsne_dbscan_3D.png)

![](images/tsne_gmm_2D.png)

![](images/tsne_gmm_3D.png)

![](images/dendogram.png)

![](images/tsne_hc_2D.png)

![](images/tsne_hc_3D.png)





