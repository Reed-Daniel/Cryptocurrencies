# Cryptocurrencies
## Project Overview
In this project we have been tasked with creating a report that includes what cryptocurrencies are currently on the trading market and how they could be grouped to create a classification system so that our client, Accountability Accounting, can feel confident in offering a new crypto investment portfolio for their customers. 

The following steps were taken to accomplish this task.
- Preprocessed the Data for PCA
- Reduced Data Dimensions Using PCA
- Clustered Cryptocurrencies Using K-means
- Visualized Cryptocurrency Results

## Results
**1)** After preprocessing our dataset for PCA, the list of avaialble cryptocurrencies was narrowed down to 532 tradable cryptocurrencies.

![total_crypto](https://user-images.githubusercontent.com/93271297/157571872-6412ced0-e342-42c2-a2ce-47c579f79eed.png)
![crypto_table](https://user-images.githubusercontent.com/93271297/157571761-2490ebf3-6dc4-4a8a-8ff6-c3cefc976b84.png)

**2)** The PCA algorithm was utilized to reduce the principal components of our tradable cryptocurrency DataFrame down to 3

![PCA](https://user-images.githubusercontent.com/93271297/157572690-24f78d80-4ddc-47a6-800d-bf94681517ae.png)

**3)** The K-means algorithm was utilized tocreate an elbow curve in order to find the best value for K from the DataFrame that was created during the previous step. Then, the K-means algorithm was used again to predict the K clusters for the cryptocurrencies’ data.

![elbow_curve](https://user-images.githubusercontent.com/93271297/157573256-9b9d553a-0df1-42a4-970e-1ecf5f487e08.png)
![K_clusters](https://user-images.githubusercontent.com/93271297/157573432-06a6e776-cddb-4f38-acc0-ad4663fb75f0.png)

**4)** 3D & 2D scatter plots were used to visualize our findings and display the distribution of our cryptocurrency clusters.

![3D_plot](https://user-images.githubusercontent.com/93271297/157574229-b82c3149-83fa-4add-9fc6-23a007cab3bb.png)
![2D_plot](https://user-images.githubusercontent.com/93271297/157574239-b5dfef5e-28a8-454c-9ab4-9a5fbc5476b6.png)

**|____________________________________________________________________________________________|**
