# K-Means Clustering with the LRFMC Method
ABC is an aviation company located in China. The company wants to know **its customer segmentation and get recommendations / actionable insight** so it can deliver its treatment optimally. The project was created to get the clusters by **applying K-Means unsupervised learning** and analyzed with **the LRFMC method** to get the customer value. The project outline includes data understanding, EDA, preprocessing, modeling, and analysis.

**K-Means clustering** is a method of partitioning data by dividing data into K clusters. Through this grouping, we can differentiate customers, and obtain their characteristics, to optimize the treatment that must be given for efficient business decision-making.

**The LRFMC method** is another method for identifying customer value, which is a development of the RFM method. Here are the five indicators of customer :
1. Length: The number of months since the member’s joining time from the end of the observation time.
2. Recency: Number of months since the member’s last flight from the end of observation time.
3. Frequency: The total number of times the member has flown during the observation period.
4. Monetary: Miles accumulated during the member observation time.
5. Coefficient: The average value of the discount factor used by the member during the observation period.

## The Results
Through this clustering with the applied LRFMC method, we obtain **the customer clusters** ordered by their **priority ranks** (**high-value** to low-value) and give each of them a customer treatment recommendation:
1. **The High Spender Loyalist**<br>To keep the high-spender, we need to maintain the discount vouchers and create a loyalty program due to their month of loyalties (Length values).
2. **The Potential-Loyalist**<br>Due to their Monetary value, we need to push this cluster to become the next loyalist customer. We can maximize the cluster's potential by maintaining the Monetary value and increasing the Length value by introducing them into loyalty benefits.
3. **The Loyalist**<br>Due to this 22% population, the Loyalist can give a potential impact on the business. We need to maintain the Recency value, by providing push notifications.
4. The Hibernating<br>We can offer a big discount voucher to attract them to the services again.
5. The Discount Hunter<br>Due to the highest Coefficient discount, and high Recency value, no need to give them a big voucher and spend many resources on them.

## File Description
- The code .ipnyb is a jupyter notebook that contains step-by-step performing unsupervised-clustering until getting the cluster and extracting actionable insight. [Click to view the notebook](https://github.com/mhfaisaluddin/K-Means-Clustering-with-the-LRFMC-Method/blob/main/K-Means%20Clustering%20with%20LRFMC%20Method.ipynb)
- The dataset .csv is the dataset used in this project, and can be downloaded from this repo or the website (for the updated data). Data source : https://www.kaggle.com/datasets/vinzzhang/aircompanycustomerinfo

### References
- Arif, R. 2020. Step by Step to Understanding K-means Clustering and Implementation with sklearn. [Medium](https://medium.com/data-folks-indonesia/step-by-step-to-understanding-k-means-clustering-and-implementation-with-sklearn-b55803f519d6)
- Indarjo, P. 2021. RFM Segmentation in E-Commerce. [Medium](https://towardsdatascience.com/rfm-segmentation-in-e-commerce-e0209ce8fcf6)
- Tao, Y. (2020). Analysis Method for Customer Value of Aviation Big Data Based on LRFMC Model. In: Zeng, J., Jing, W., Song, X., Lu, Z. (eds) Data Science. ICPCSEE 2020. Communications in Computer and Information Science, vol 1257. Springer, Singapore. https://doi.org/10.1007/978-981-15-7981-3_7
