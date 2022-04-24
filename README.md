# SC1015_mini_project_grp_5
Done by Nicole, Yong Jian, Shawn

## What we want to explore:
  1.Explore which purchasing habits differentiate Males and Females apart. From this, how successful will the model created be in predicting whether a customer is a Male of Female?<br /><br />
  2.For each variable that distinguishes male and female customers, we will try to explore the rationale behind it to gain further insights.
  
## Data Sets from:
Title: Supermarket Sales<br />
URL: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales?datasetId=205965&sortBy=voteCount

## About our Dataset
The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. It contains data for each customer, including their gender, product line of item purchased, payment method, city, time of visit, total spending, etc. 

## Our Presentation Slide:
View From: https://docs.google.com/presentation/d/14F73vWEWDeXvqPMwBpttYmvqk1Szhm5aEjXTaxSfjis/edit?usp=sharing

Download From: https://github.com/hibye0714/SC1015_mini_project_grp_5/blob/494281658422a5d2d5292764e59391bc636c1fa0/Group%205%20Slides.pptx

## Conclusion(Insights):
We found that the most useful variables to predict Gender of a Customer are the time they visited, the total amount they spent, the rating they gave, product line of items bought and the day of visit.

The best improved accuracy we could reach when predicting a customer’s gender is 0.64, which is when we implemented random forest that utilises both the numerical and categorical variable combined.

## Recommendation:
1.Increase the quantity of Fashion & Accessories products (most popular product line for female)  in store to target to more females (as they have an average higher spending) -- in order to increase sales<br /><br />
2.Implement a ladies discount every Tuesday & Saturday (from opening hours to afternoon 3pm), where frequency of females visiting is highest -- to attract more female customers and increase sales

## In our jupyter notebook, we have added in a table of content to help with navigation (only works in Jupyter Notebook)
<img width="492" alt="Screenshot 2022-04-24 at 4 36 54 PM" src="https://user-images.githubusercontent.com/48339717/164967974-72f1751e-6e57-473a-b555-bf71230aa141.png">
 
## What did we learn from this project:
1. Ability to identify and come up with data oriented problems and data-driven decisions<br />
2. Basic tools and techniques of data handling<br />
3. Different models for Exploratory Data Analysis<br />
4. Machine Learning Models for prediction<br />
4. Apply basic machine learning tools to extract inferential information from the data

## Machine Learning Models Used:
 1.Multivariate Classification Tree Tree<br />
 2.Logistics Regression with one hot encoding<br />
 3.Multivariate Classification Tree with one hot encoding<br />
 4.Random Forest
 
## Workload Distribution:
1.Nicole<br />
  * Data Cleaning
  * EDA Numerical Data
  * Multivariate Classification Trees
  * One-hot encoding & Logistics Regression

  
2.Yong Jian<br />
  * Data Cleaning
  * Random Forest
  * EDA for Categorical Data
  * One-hot encoding


3.Shawn<br />
  * One-hot encoding
  * Data Cleaning
  * Debugging of Warnings 
  * Optimizing Plot Sizes for all data points to fit

 
 ## References
https://stackoverflow.com/questions/38067704/how-to-change-the-datetime-format-in-pandas<br />
https://datascientyst.com/convert-datetime-day-of-week-name-number-in-pandas/<br />
https://towardsdatascience.com/decision-trees-explained-3ec41632ceb6<br />
https://stackoverflow.com/questions/59447378/sklearn-plot-tree-plot-is-too-small<br />
https://analyticsindiamag.com/when-to-use-one-hot-encoding-in-deep-learning/<br />
https://machinelearningmastery.com/one-hot-encoding-for-categorical-data/<br />
https://altair-viz.github.io/gallery/index.html#interactive-charts<br />
https://www.analyticsvidhya.com/blog/2015/11/easy-methods-deal-categorical-variables-predictive-modeling/<br />
https://www.shanelynn.ie/merge-join-dataframes-python-pandas-index-1/<br />
https://levelup.gitconnected.com/decision-tree-regression-df9e24ffe59a<br />
https://levelup.gitconnected.com/random-forest-regression-209c0f354c84
