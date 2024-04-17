## Introduction
We've carried out a thorough examination of past auto sales data to offer insightful recommendations for improving inventory control tactics. Our machine learning-based forecasting algorithm provides practical insights into upcoming pricing trends. Our main conclusions and suggestions to assist your dealership make the best inventory decisions are presented in this study.

### 1. Analysis of Data:

We started our investigation by looking through a large dataset that included a variety of characteristics from previous auto sales. After completing the data cleaning process, our dataset was refined to include 70,000 rows of data:

![Logo](https://github.com/Ziggy-Z/What-Drives-the-Price-of-a-Car/blob/main/images/dataInfo.PNG)

Numerical value analysis:

![Logo](https://github.com/Ziggy-Z/What-Drives-the-Price-of-a-Car/blob/main/images/dataDesc.PNG)

We found important patterns and connections between many variables and car pricing using exploratory data analysis.

![Logo](https://github.com/Ziggy-Z/What-Drives-the-Price-of-a-Car/blob/main/images/heatMap.png)

Let's see these correlations compared to our price:

![Logo](https://github.com/Ziggy-Z/What-Drives-the-Price-of-a-Car/blob/main/images/priceCorr.png)

We observe a strong positive correlation between price and year. Let's delve into our models to identify additional underlying correlations between every column in our dataset.
### 2.  Predictive Modeling: 
Using machine learning techniques, we created a predictive model that can estimate car costs based on important characteristics. We ran 3 predictive models and these were the performance of each model.

#### Error comparison:
These error comparisons provide insights into the performance of each model, with lower values indicating superior performance.

![Logo](https://github.com/Ziggy-Z/What-Drives-the-Price-of-a-Car/blob/main/images/MSE_comp.png)

#### R<sup>2</sup> comparison:
These R<sup>2</sup> comparisons offer a perspective on the performance of each model, where higher values signify better performance.

![Logo](https://github.com/Ziggy-Z/What-Drives-the-Price-of-a-Car/blob/main/images/R_comp.png)

The model we picked displayed good performance measures, highlighting its ability to reliably anticipate future sales prices without any overfitting.

### 3. Key Features Driving Prices:

The investigation revealed the top three factors that have the most influence on car prices:

![Logo](https://github.com/Ziggy-Z/What-Drives-the-Price-of-a-Car/blob/main/images/importance.png)

* Year: Newer model years typically attract greater prices, reflecting technological developments and design preferences.
* Odometer: Lower mileage correlates with higher costs, indicating that consumers prefer well-maintained vehicles with less wear and tear.
* Cylinder: The number of cylinders in a vehicle's engine is also an important price factor, with larger cylinder counts frequently indicating better performance and price points.

### 4. Recommandations:
Based on our findings, we offer the following measures for improving inventory management and price decisions:

* Prioritize purchasing newer model years with lower mileage and higher cylinder counts to capitalize on market demand for high-performance vehicles.
* Pricing strategies should be reviewed and updated regularly, taking into account market conditions, competitor evaluation, and customer preferences.
* Create customized marketing efforts that showcase inventory strengths such as low-mileage and high-performance cars.
* Consider diversifying your inventory by stocking a variety of vehicle types, including sedans, SUVs, trucks, and hybrids.
* Analyze market trends and customer preferences to identify emerging trends and ensure your inventory aligns with changing consumer demands.

### 5. Conclusion:

Our analysis gives useful insights into the biggest drivers of car prices and practical recommendations for improving inventory management tactics. Your dealership may make informed choices to remain competitive in the evolving used car market and improve profits by using advanced analytics and predictive modeling approaches.
