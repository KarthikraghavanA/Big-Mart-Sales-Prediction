# *Machine Learning Project 2 - BigMart Sales Prediction*



In this project, We will explore the Supermarket industry using the BigMarket dataset, We will predict the sales price for a given product and store.
We will do a lot of Feature Engineering and Data Preprocessing with lots of Visualization in handling the dataset.

This is a **Regression** problem and we will use some regression algorithms such as

*   Linear Regression
*   Decision Tree Regressor
*   Random FOrest Regressor
*   XG Boost Regressor


Dataset Link - https://www.kaggle.com/code/hiralmshah/bigmart-sales-prediction

Dataset Information:

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

Attribute Explanation - 

* Item_Identifier: Unique product ID
* Item_Weight: Weight of product
* Item_Fat_Content: Whether the product is low fat or not
* Item_Visibility: The % of total display area of all products in a store allocated to the particular product
* Item_Type: The category to which the product belongs
* Item_MRP: Maximum Retail Price (list price) of the product
* Outlet_Identifier: Unique store ID
* Outlet_Establishment_Year: The year in which store was established
* Outlet_Size: The size of the store in terms of ground area covered
* Outlet_Location_Type: The type of city in which the store is located
* Outlet_Type: Whether the outlet is just a grocery store or some sort of supermarket
* Item_Outlet_Sales: Sales of the product in the particulat store. This is the outcome variable to be predicted.

-----------------------------------------------------------------------------------------------------------------------------

We see the below accracies for the models


![image](https://user-images.githubusercontent.com/112689649/211140555-c73099b3-5ecb-4d4d-9df5-9a8de56878b1.png)

-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
We can also try a couple of other things 

* Feature Engineering could have been done in other ways
* We can split using train_test_split from model_selection
* Dealing with Outliers
* Scaling the dataset
* Other techniques :
    *   Ridge Regression
    *   Lasso Regression
    *   Support Vector Regression
    *   Bagging Regression
    *   Gradient Boosting Regression
    
