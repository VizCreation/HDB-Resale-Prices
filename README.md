# HDB-Resale-Prices
HDB Resale Prices from Year 2013 to Jan 2024
## Problem Statement
1. Has the Resale flat prices been increasing or falling over the past few years? Is it a good time to buy or sell now?
2. What is the Maximum resale price for flats sold?
3. Which flat size has more transactions and would be easier to find buyers?
4. Which are the cheapest and most expensive towns?

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
![]()
