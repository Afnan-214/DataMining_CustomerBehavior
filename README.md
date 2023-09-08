# Group project: Stores' Data Mining to detect customers behavior
## Dataset discription
The dataset contain data about 150 store of The FOODmart supermarket chain, which is one of the leading grocery stores in Australia.<br> 
It describes the nature of each store in terms of sales, Gross profits, location, holidays, home delivery, parking space, number of staff, managers' information and Cost of the basket of food items.
## Target 
<ol>
  <li>Analyse the natural of the stores in this super market chain</li>
  <li>Help the company to make informed desicion about making changes in its store</li>
 <li>Identify the customer preferences by analysing the features that improve the store sales.</li>
</ol>

## Project phases
### 1. Pre-Processing 
  *Data transformations* 
  *Feature selection* 
  *Handle outliers* 
  
### 2. Exploratory analysis
  *Data Visualization* 
  *variables statistics sammary* 
  
### 3. Machine learning Algorithms
* Regression
  > 
* Clustering
  > Preparing the data <br> Applying elbow method and visualize it using yellowbrick library to display the elbow point for k value in k-means <br> Use PCA method to reduce dimensionality.
* Neural Network
  >
* Association Rule
  > 

### 4. Insights

*1- From Regression:*
   1. The Advertise expenses has the most positive impact compared to " Wages $m, Competitors, Basket:2014" on the sales. <br>
   2. The number of effective staff has a high positive impact on the sales with about  increasing the sales by $886800 for a unit.<br>
   3. The available car spaces also have high positive impact on the sales as it will increase by about $646300 for unit.<br>

*2- From clustering:*
   1. cluster 0 has the higher gross profit this can help to detect features to improve other clustering as offering home delivery services.<br>
   2. stores that assigned to cluster 1 have high features and the company can use its strategies to improve the other stores.<br>
   3. cluster 2 stores have the lower features and need more attention from the company managers. they can improve some of its feature and change its managers to more experience ones.<br>

*3- From Neural Network:*
   1. neural network has performed reasonably well, with a relatively low MSE, RMSE,MAE and MAPE and with high Explained variance<br>
   2. This model can be used to predict sales of store with specific characteristics, and help the supermarket chain to make informed decision about opening a new store<br>

*4- From Association Rule:*
   1. The Sales and the number of effective staff are strongly related and have Mutual effect on each other<br>
   2. Sales and the number of available parking space are strongly related<br>
   3. The stores with female managers are more likely to have low advertising expenses. <br>
   4. Expected stores with high number of competing supermarkets have low profit<br>

##### Customers prefer stores with :

 1. large parking spaces<br>
 2. high number of full time staff<br>
 3. low prices of main basket items<br>
 4. Home delivery<br>
 5. Opens on Sundays<br>
