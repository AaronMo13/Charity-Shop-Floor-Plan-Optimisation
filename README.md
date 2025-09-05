# Charity Shop Floor Plan Optimisation
## Project Overview
This project is aimed towards boosting a local charity shop's sales revenue, who have not had any previous data analysis performed. Following discussion with the shop's manager, we agreed that it would be of value to look into seasonal and monthly sales trends to observe whether we have the correct amount of stock displayed on the floor for particular categories throughout the year. The company has a vast amount of data but for this project we focus specifically on their space management reports. As a brief overview this data tells us the weekly sales revenue and quantity sold for each category and sub category of items as well as the amount of floor space they occupy. We provide insights and recommendations for the optimal floor plan for the amount of space each category should take up based on the previous three and a half years of data. The focus of this report will mainly be on the findings for September since the project was completed in August, therefore we can look to implement our first changes in September.

## Data Structure
We use the charity shop's space management entry data reports dating back to 27th March 2022 until 20th July 2025. Constructed from this dataset we also have two other datasets: optim bays and optim rev. These two additional datasets are the results of our optimisation of the floor plan and are used to display these findings in Power BI. Optim bays contains the predicted optimal and average observed number of bays each category occupies in the shop for each month and optim rev contains the predicted optimal revenue and average observed revenue for each month. One bay is worth a meter of space in the shop. The data structure is shown in the diagram below.

<img width="1023" height="667" alt="data relationships" src="https://github.com/user-attachments/assets/ac8d5c18-e425-4d4f-beac-abb2c1889609" />


## Executive Summary
The bar chart shows the predicted number of optimal bays against the average actual number of bays for each category in September, based on the data for 2024 (top graph) and for 2022-2024 (bottom graph). Firstly, it is important to note that we set a maximum for all categories to not exceed 3 bays, therefore where we see the recommendation to decrease the number of bays for the home category we ignore this because we set a limit of 3.

<img width="655" height="368" alt="September - optimised floor plan" src="https://github.com/user-attachments/assets/0a9cdb2b-565f-4157-977f-29fa0b050917" />

We see for Septmeber that if we use the suggested number of bays for the categories that the average weekly sales revenue is predicted to grow from £3341 to £3748 with a 12.18% increase based on the data from 2024, and grow from £3554 to £4003 with a 12.64% increase based on all years worth of data. Using the data from 2024 as well as the data from all years we see that it is suggested we display more ladies tops, mens tops, ladies knitwear, ladies trousers, ladies coats, media and mens shoes and accessories. We also see it is recommended to decrease the number of ladies accessories, ladies dresses, ladies shoes and clothing promotion clothes. The largest differences suggested based on the data from 2024 are: increasing ladies tops from 1.75 to 3 bays, increasing mens tops from 1 to 2 bays, decreasing ladies dresses from 2 to 0.5 bays and decreasing ladies shoes from 1 to 0.25 bays. These numbers are very similar to those suggested by the data of all years, therefore giving us further evidence that implementing these changes will benefit the shop. However, we will look into this further below.

## Detailed Insights
We will now have a deeper look into the data for September and then some of the categories which are recommended to be changed by the optimisation above.

<img width="656" height="370" alt="Initial Insights" src="https://github.com/user-attachments/assets/09cb4a8b-3987-4849-b35a-679622032441" />

Firstly, we will have a look into the overall trends for September. The top graph above shows the average weekly number of bays and average weekly revenue per bay for each category and the bottom graph shows the average weekly revenue and average weekly quantity of items sold for each category in September. We see that most frequently sold items are from the categories books, home and kids non clothing and the categories with the highest average weekly revenue in September are home, ladies tops and books. We also see that home, books and kids non clothing occupy have the highest number of bays in the shop. However, ladies tops, mens tops and ladies trousers have the highest average revenue per bay, implying maybe we should increase their number of bays. Conversely, BIG (bought in goods) cards, BIG xmas cards and ladies dresses have the smallest average revenue per bay, suggesting maybe we should decrease their number of bays. Bought in goods have a fixed amount each month so we will not look in detail at these. We will now examine some of the categories further.

<img width="650" height="363" alt="Ladies Dresses - line" src="https://github.com/user-attachments/assets/5662f6b8-69e5-41a5-abfd-eb4d568749c4" />

We will begin with ladies dresses. The bottom line graph shows the trend for quantity of dresses sold throughout the 3 and a half years. It shows more dresses are sold in the summer and less in the winter, as we would expect. The top line graph is of more interest to us here, it shows the percentage of floor space the dresses occupy as well as the percentage of the shop's revenue dresses create. We can see that for the last 3 winters the percentage of space occupied by dresses is consistently higher than the percentage of revenue they generate for the shop. We should also note that in the winter of 2024 the percantage of revenue generated by dresses is close to 0% on numerous occassions, with its lowest being 0.31%, however the percantage of space is roughly 4.5%. This implies we should look to decrease the number of dresses on display throughout the winter even further and put something else in their place instead, as is suggested by the optimisation graph above.

<img width="658" height="368" alt="Ladies Tops - monthly" src="https://github.com/user-attachments/assets/99ceebea-482d-46fb-93a6-0e36c8d0b505" />

Next we will look at ladies tops. The graph in the top left shows the average weekly quantity of ladies tops sold and the average weekly revenue they generated for each month, and the graph in the bottom right shows the average weekly number of bays ladies tops occupy and the average weekly revenue a bay of ladies tops generates for each month. We can see that the number of bays are higher for the summer months compared to the winter months, which explains the pattern of higher revenue and quantity of ladies tops sold shown in the top left graph. However, in September and October we see a 13% and 17% monthly increase in average revenue generated per bay of ladies tops, rising from £209 in August to £276 in October, suggesting we should not be decreasing the number of bays for this category, which is again implied from the optimisation graph discussed above.

<img width="656" height="368" alt="Ladies Accs - monthly" src="https://github.com/user-attachments/assets/bfc25910-675b-4c32-9d10-4c7ef193bb06" />

Finally we will look at ladies accessories. From the graph in the top left we can see that the average weekly revenue drops sharply from July to September, with a decrease from £218 to £146. The average quantity sold also drops from 50 to 35 in this period. Similarly, from the bottom right graph we see that the average revenue per bay for ladies accessories reaches its minimum in September. All of these points imply we should decrease the number of bays worth of ladies accessories. However, we should also note the rapid increase in the average revenue per bay of 57% from October to November where we should be ready to increase the number of bays back up again. All other categories can also be evaluated in this way to determine if any changes should be made.

## Recommendations
Following on from the executive summary and the detailed insights section we can provide some recommendations for September:

- Decrease quantity of ladies dresses to 0.5 bays and replace with some ladies tops, ladies trousers, ladies knitwear and ladies coats (majority ladies tops and ladies knitwear)
- Decrease quantity of mens coats, jackets and suits to 0.25 bays and replace with mens tops
- Decrease quantity of ladies accessories to 0.75 bays and ladies shoes to 0.25 bays and replace with mens shoes and media (potentially also some more mens tops)
## Technical Details

## Assumptions
