# Tiller by SumUp
## Goal of the project
The purpose of this project is to deep dive into the dataset of Tiller, a business app, that shows all the spending of their customers in one simple dashboard. As London-based global payment services provider SumUp which mainly owns mobile point-of-sale (mPOS) acquired Tiller in 2021, I analyzed their data from devices with main Business Objectives:
- Highlight how data can be leveraged to grow a customer's business i.e. restaurant in this project.
- Provide a simple-to-use dashboard for business owners

## Tableau Dashboard
The interactive Dashboard based upon three metrics segmentation is shown in the image below while the subsequent link is also attached. The metrics are:
1. Revenue overview
2. Payment types and performance
3. Product segmentation

![Dashboard](Media/Dashboard.png)

Click [here](https://public.tableau.com/app/profile/usama.zafar.qureshi/viz/Tiller/Dashboard1) for an interactive tableau dashboard.

## Data Processing and Cleaning
Data is processed and cleaned with the help of Python libraries by observing:

- Check for missing data with the help of conditional formatting, removing and filling null values of columns\
- Correctly format required columns and their values

## Analysis Approach
The main analysis approach was to understand Revenue distribution over time. Understanding Payment types based upon the times to find the best sales time. Then, in the end, categorize the data into the most profitable categories and products for a restaurant.

## Datasets Used
The datasets used:

Comes in four Excel sheets from the business owner named Order_data, Order_line, Payment_data, and store_data.\
All have the same 501 rows with 500 being pure data and the other row being the column headers.\
This company device data was recorded between **2016-05-26** to **2020-10-11**.\
It contains the data of orders at different restaurants.

## Built with
+ Python 3.10.11
+ Google Colab
+ Tableau

## Author
Chirag Arya - [Github Profile](https://github.com/AryaChirag)
