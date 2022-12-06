# K-Means Clustering with the LRFMC Method
Created to apply K-Means unsupervised learning with the LRFMC method from the paper. The project outline includes data understanding, EDA, preprocessing, modeling, and analysis.

**K-Means clustering** is a method of partitioning data by dividing data into K clusters. Through this grouping, we can differentiate customers, and obtain their characteristics, to optimize the treatment that must be given for efficient business decision-making.

**The LRFMC method** is another method for identifying customer value, which is a development of the RFM method. Here are the five indicators of customer :
1. Length     : The number of months since the member’s joining time from the end of the observation time.
2. Recency    : Number of months since the member’s last flight from the end of observation time.
3. Frequency  : The total number of times the member has flown during the observation period.
4. Monetary   : Miles accumulated during member observation time.
5. Coefficient: The average value of the discount factor used by the member during the observation period.

Through the clustering method, we obtain the customer clusters ordered by their priority ranks (**high-value** to valueless):
1. **The High Spender Loyalist**
2. **The Potential-Loyalist**
3. **The Loyalist**
4. The Hibernating
5. The Discount Hunter

## File Description
- The code .ipnyb, is a jupyter notebook that contain step-by-step performing unsupervised-clustering. [Click to view the notebook](https://github.com/mhfaisaluddin/K-Means-Clustering-with-the-LRFMC-Method/blob/main/K-Means%20Clustering%20with%20LRFMC%20Method.ipynb)
- The dataset .csv, is the dataset that used in this projcet, and can be downloaded from this repo or the website (for the updated data). Data source : https://www.kaggle.com/datasets/vinzzhang/aircompanycustomerinfo
