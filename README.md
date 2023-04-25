# Customer segmentation on banking transaction data

* The customer data includes features such as transaction frequency, credit limit, balance amount, etc.
* Explored the dataset, filled some missing values and got some insights about statistics of several features
* Explored the distribution of the features
* Calculated the correlation matrix
* Normalized the dataset
* Used K-Means clustering algorithm and elbow method to define the amount of clusters (7)
* Applied PCA for visualizing the dataset

## Results:

* 3 interesting clusters:
  * The first cluster are customers who either don't have much money or have a banking account at another bank and use their account only as a second account. They are also careful and pay a decent amount of their loans as a full payment.
  * The second cluster are customers who don't care to pay much in interest charges as they only pay about 4 % in full payment. Those customers are very lucrative for the bank.
  * The third cluster are customers which could be called VIP. They have a very high credit limit and spend very much money. The bank could target those customers to further increase their spending habit.

| Cluster No. | Balance | PRC of full payment | Cash Advance | Purchases | Credit Limit |
| --- | --- | --- | --- | --- | --- |
| 1 | **110.9 $** | 23 % | 336.0 $ | 322.8 $ | 198.8 $ | 3716.5 $ |
| 2 | 4896.3 $| **3.9 %** | **5049.7 $** | 526.0 $ | 8017.8 $ |
| 3 | 5448.2 $ | **51.5 %** | 970.1 $ | **27916.6 $** | **16043.5 $** |
