# [Project 1: Fantasy Football](https://github.com/brock-ricker/fantasy_football)

This project is a work in progress and is still being updated regularly as I build more ML models and implement more database features.

Summary
---
* Collected data from numerous online sources; APIs and Web scraping.

* Used data to build SQL database.

* Exploratory analysis of Fantasy Football analytics.
![image](https://user-images.githubusercontent.com/99829862/178310349-d1f9e728-06e5-4cb8-a297-4f147048f94e.png)
  * Distribution of "starter" scores at each position

* Implemented ML models to make predictions about individual player performance.

| Model | R2 | MAE | MSE | RMSE |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| GBR_MAE | 0.4464 | 4.25 | 37.97 | 6.16 |
| GBR_RMSE | 0.4682 | 4.45 | 36.48 | 6.04 |

# [Project 2: Online Shoppers Purchasing Intent](https://github.com/brock-ricker/Online-Shoppers-Purchasing-Intent)

Summary
---
* Used web browsing data to build supervised and un-supervied ML models.

* Performed customer segmentation based on web browsing data.
![image](https://user-images.githubusercontent.com/99829862/178315857-de2b5a09-7a43-4ee1-afba-e6434eae4339.png)
  * Mean values for a selection of features, by customer segment.

* Implemented Random Forest Model to predict if a shopping session would end in a purchase (1=Yes, 0 = No)
![image](https://user-images.githubusercontent.com/99829862/178316756-60bcbdc4-18b3-4592-87ef-67367eecffec.png)
  * Confusion matrix for Random Forest Model.
  
# [Project 3: Food_Sales_Predictions](https://github.com/brock-ricker/food_sales_predictions)

Summary
---
* Analyzed sales data from 10 store locations in 3 different sizes, and 4 outlet type categories.
* Predicted the total sales in dollars of a variety of items using a Decision Tree Regressor.
 * R2: 0.5950, MAE: 737.63, MSE: 1,117,324.23, RMSE: 1,057.04

