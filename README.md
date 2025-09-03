# Charity Shop Floor Plan Optimisation
## Project Overview
This project is aimed towards boosting a local charity shop's sales revenue, who have not had any previous data analysis performed. Following discussion with the shop's manager, we agreed that it would be of value to look into seasonal and monthly sales trends to observe whether we have the correct amount of stock displayed on the floor for particular categories throughout the year. The company has a vast amount of data but for this project we focus specifically on their space management reports. As a brief overview this data tells us the weekly sales revenue and quantity sold for each category and sub category of items as well as the amount of floor space they occupy. We provide insights and recommendations for the optimal floor plan for the amount of space each category should take up based on the previous three and a half years of data. The focus of this report will mainly be on the findings for September since the project was completed in August, therefore we can look to implement our first changes in September.

## Data Structure
We use the charity shop's space management entry data reports dating back to 27th March 2022 until 20th July 2025. Constructed from this dataset we also have two other datasets: optim bays and optim rev. These two additional datasets are the results of our optimisation of the floor plan and are used to display these findings in Power BI. Optim bays contains the predicted optimal and average observed number of bays each category occupies in the shop for each month and optim rev contains the predicted optimal revenue and average observed revenue for each month. One bay is worth a meter of space in the shop.

## Executive Summary
The graph shows the predicted number of optimal bays against the average actual number of bays for each category in September, based on the data for 2024 (top graph) and for 2022-2024 (bottom graph). Firstly, it is important to note that we set a maximum for all categories to not exceed 3 bays, therefore where we see it recommends to decrease the number of bays for the home category we ignore this because we set a limit of 3.

<img width="655" height="368" alt="September - optimised floor plan" src="https://github.com/user-attachments/assets/0a9cdb2b-565f-4157-977f-29fa0b050917" />

We see for Septmeber that if we use the suggested number of bays for the categories that the average weekly sales revenue is predicted to grow from £3341 to £3748 with a 12.18% increase based on the data from 2024, and grow from £3554 to £4003 with a 12.64% increase based on all years worth of data. Using the data from 2024 as well as the data from all years we see that it is suggested we display more ladies tops, mens tops, ladies knitwear, ladies trousers, ladies coats, media and mens shoes and accessories. We also see it is recommended to decrease the number of ladies accessories, ladies dresses, ladies shoes and clothing promotion clothes. The largest differences suggested based on the data from 2024 are: increasing ladies tops from 1.75 to 3 bays, increasing mens tops from 1 to 2 bays, decreasing ladies dresses from 2 to 0.5 bays and decreasing ladies shoes from 1 to 0.25 bays. These numbers are very similar to those suggested by the data of all years, therefore giving us further evidence that implementing these changes will benefit the shop. However, we will look into this further below.
## Detailed Insights


## Recommendations

## Technical Details

## Assumptions
