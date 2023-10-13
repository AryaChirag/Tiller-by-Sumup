# Tiller by SumUp
## Goal of the project
The purpose of this project is to deep dive in dataset of Tiller, a business app to show all spending of their custromers in one simple dashboard. As London based global payment services provider SumUp which mainly owns mobile point-of-sale (mPOS) acquired Tiller in 2021, I analyzed their data from devices with main Business Objectives:
- Highlight how data can be leveraged to grow a custromer business i.e. restuarant in this project.
- Provide simple-to-use dashboard for business owners

## Tableau Dashboard
The interactive Dashboard based upon three metrics segmentation is shown in image below while subsequent link is also atatched, metrics are:
1. Revenue overview
2. Payment types and performance
3. Product segmentation

![Dashboard](Media/Dashboard.png)

Click [here](https://public.tableau.com/app/profile/usama.zafar.qureshi/viz/Tiller/Dashboard1) for interactive tableau dashboard.

## Data Processing and Cleaning
Data is processed and cleaned with the help of Python libraries by observing:

- Check for missing data with the help of conditional formating, removing and filling null values of columns\
- Correctly format required columns and their values

## Analysis Approach
Main analysis approach was to understand Revenue distribution over the time. Understanding Payment types based upon the times to find best sales time. Then in the end, categorize the data in to most profitable categories and products for a restaurant.

## Datasets Used
The datasets used:

Comes in four excel sheets from the business owner named as Order_data, Order_line, Payment_data, and store_data.\
All have same 501 rows with 500 being pure data and the other one row being the column headers.\
This company device data recorded between **2016-05-26** to **2020-10-11**.\
It contains the data of orders at different restaurants.

## Built with
Python\
Tableau

## Author
Chirag Arya - Github [Profile](https://github.com/AryaChirag)
