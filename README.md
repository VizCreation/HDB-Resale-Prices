# HDB-Resale-Prices
HDB Resale Prices from Year 2013 to Jan 2024
## Problem Statement
1. What is the Maximum resale price for flats sold? How much has it increased?
2. Which flat size has more transactions and would be easier to find buyers? 
3. Has the Resale flat prices been increasing or falling over the past few years? Is it a good time to buy or sell now?
4. Which are the cheapest and most expensive towns?
5. In the past year (2023), which are the towns with the highest number of flats sold?

## Data Sourcing
The data used is sourced from the Singapore's Government Agency Website data.gov.sg. The full data is a combination of 3 data sets with links provided below:
1. https://beta.data.gov.sg/collections/189/datasets/d_2d5ff9ea31397b66239f245f57751537/view
2. https://beta.data.gov.sg/collections/189/datasets/d_ea9ed51da2787afaf8e51f827c304208/view
3. https://beta.data.gov.sg/collections/189/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view

## Data Transformation/Cleaning
Data was cleaned and transformed with the Power Query Editor in Power BI and by creating new measures using DAX. Some of the applied steps include:
* Combining the 3 data sets into 1 main table
* Classifying the Remaining Lease period into a Range (eg. 51- 60 years, 61- 70 years etc...). For info: The remaining lease period ranges from 0 - 99 years.
* Extracting only the Year from "Date of Sale"
* Using DAX to create new measures and Dynamic Title based on selected Filter

## Data Visualisation
![Main Dashboard Page1](https://github.com/VizCreation/HDB-Resale-Prices/assets/157504708/d30bebf8-e8bc-4128-ba0f-1f2fa7b1c320)


![Dashboard Page2](https://github.com/VizCreation/HDB-Resale-Prices/assets/157504708/808a2534-cdd6-4d35-89de-7746d9aedcfa)


## Findings/Conclusion
1. From Dashboard 1 and 2: Based on the top bar chart in Dashboard 1, the max resale price has been increasing since 2013 to Dec 2023. The highest resale price recorded in Year 2023 was $1.5 million for a 5room flat in Bukit Merah town.
2. From Dashboard 1: Based on the Pie Chart, 4-room flat type takes up 41.5% of the total flat sold for the past 11 years. It may be easier to sell 4-room flat in the future as the transaction % is the highest indicating higher market interest.
3. From Dashboard 1: Based on the bottom bar chart, the resale flat prices seems to have fallen from 2013 to 2018 and started rising again from 2019 onwards.
4. From Dashboard 2: The most expensive towns to buy a flat in is in Bukit Merah and Central Area of Singapore, while the cheapest towns are Choa Chu Kang and Sembawang.
5. From Dashboard 2: Based on the scattered plot, most people are selling their flats in Punggol, Sengkang, Woodlands and Yishun. One possible reason could be these estates has quite a number of BTO flats built in the recent years and these flat might have just reached the 5 year MOP, so many first-time buyers have sold their flat to upgrade. 
