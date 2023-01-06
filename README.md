# Predicting Customer Churn

<img src="https://i.imgur.com/wOuTBdJ.png" />

<h2>Problem statement</h2>
In 2019, a large telecom operator lost $1.21 million to customer churn because 1,010 of customers churned. From my analysis, in 2020, the churn losses has increased to $ 4.71 million as a result of 3925 of our customers churning. The situation is getting worse and something needs to be done about it. The proposed solution is to attempt to use machine learning to predict customers who are likely to churn to inform marketing action.
<br></br>
In this project, I attempt to use machine learning to predict customers who are likely to churn to inform marketing action

<h2>Model Evaluation Metric</h2>

For the purposes of business evaluation, model gain, thus the amount saved from churn losses using the model is computed as 

$$($500×True Positives) + (-$50 × False positives) + (-$1200 × false negative)$$

<h2>Languages and Libraries Used</h2>

- R programming language 
- [List of libraries](https://github.com/graphshade/customer_churn/blob/main/renv.lock)

<h2>Environment Used </h2>

- <b>Ubuntu 22.04.1 LTS</b>


<h2>Key Insights:</h2>

1. Customers without paperless billing setup turn are two times more likely to churn than customers with paperless billing setup
2. Network speed, 5G or 4G seems not to influence customer churn
3. Similar to network speed, the customers phone model seems to have marginal influence on customer churn
4. Using the machine learning model, the telecom company is estimated to save between 12% to 24% on churn losses. Amounting to $265,000 to $996,000 on average in dollar terms.


<h2>Reproducing the Analysis:</h2>

<p align="left">

1. [Install R and RStudio](https://techvidvan.com/tutorials/install-r/)
 
2. Clone the project: Run this from the command line
 
 ```commandline
 git clone https://github.com/graphshade/customer_churn.git
 ```
 
3. Install Required Libraries Using Virtual Environment: 
   
   You may install the libraries directly on your computer however, using the virtual environment library `renv`. [Follow this guide to install renv](https://www.youtube.com/watch?v=yc7ZB4F_dc0)
   1. Open the app.R file in RStudio
   2. In the RStudio console run `renv::init()` to initiate the renv virtual environment and install the required libraries from the [renv.lock](https://github.com/graphshade/credit_card_fraud/blob/main/renv.lock) file 
