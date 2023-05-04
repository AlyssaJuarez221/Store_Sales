![StoreSales (440 × 388 px)](https://user-images.githubusercontent.com/111559921/232253940-33079fde-7ae8-408e-b077-9b9c9876cf64.png)


  ## Summary
In this project I use a linear-regression model, randomforestregressor and a neural network to predict the store sales.

## Overview
Grocery stores have a constant issue, figuring out how much product to keep on hand. Too much product could lead to spoiled food or outdated styles while too little means the business loses out on potential sales. That’s where data science comes in. Through regression models, we can predict how much a store will sale based on previous experience and minimize loss. 



  ### Data
  * Instances: 3 million 
  * Features: 6 
  * 121.87 MB
  * Supervised
  * Output Type: Numerical


  ## Models
  * Linear Regression model
  * RandomForestRegressor
  * Neural Network
  
  ## Performance Comparison 
  * Linear Regression model
    *Score: 0.3396043757938785
  * RandomForestRegressor
    *Score: 0.8979041145244615
  * Neural Network
    * Score: 51.937977546440884
    
  ## Conclusion
  While the Randomforestregressor model was the best in this instance, I believe it is because I am not yet great at building a neural network.
    
  ## Future Work 
  If this project taught me anything, it't that I need to work on my neural network skills. I hope to prefect them in the near future.
  
  ##How to Reproduce Results
  Plug in your dataset, identify and rewrite your X,y and youre good to go!
  
  ## Overview of files in repo
  * code.ipnyb - the jupyter notebook containing all of my code and findings
  
  ## software setup 
* numpy
* matplotlib
* pandas
* seaborn
* sklearn.linear_model import LinearRegression
* sklearn import linear_model
* sklearn.ensemble import RandomForestRegressor
* keras.models import Sequential

  
  ## Data
  * https://www.kaggle.com/competitions/store-sales-time-series-forecasting

