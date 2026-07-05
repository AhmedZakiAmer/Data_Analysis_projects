# Project Title: Sales Performance Analysis Contoso Dataset

# Dataset Overview:
dataset from +15K rows of retail sales transactions with date time between 6-2016 to 6-2019

# Audience & Dashboards:
## Dashboard 1 CEO: 
    1- Our Profit margin is 57% through last 3 yeasrs (6-2016 to 6-2019)
    2- Revenue decreased from 2017 to 2018  
    3- North America revenue declining since 2017 peak while Asia shows consistent growth

![CEO Dashboard](CEO_Dashboard.png)

## Dashboard 2 Sales Manager: 
    1- Overall sales declined in 2018 across all channels
    2- Camera category revenue declined significantly in 2018 
    3- stores still our lead channel
    4- Cell phones buy highr in Asia through time as it achieved Growth rate around 20%

![Sales Dashboard](Sales_Dashboard.png)

## Dashboard 3 Product Manager: 
    1- our ROI is 135% through last 3 yeasrs (6-2016 to 6-2019)
    2- Our Revenue Growth 2017 to 2018 is -9.4%
    3- Computers lead profit across all regions.

I used log scale for qty & price chart to prove the relation and suggest to merge between some products to increase our AOV
![Product Dashboard](Product_Dashboard.png)

# Tools
    1- Microsoft Excel (Pivot Tables, Dashboard Design, SUMIF, VLOOKUP)
    2- Microsoft Power BI (DAX, Interactive Dashboards, Slicers)

# Power BI V2 Improvements
    1- Restructured data model to star schema (fact + dimension tables)
    2- Created dedicated Measures table no calculated columns, 
    3- all metrics defined as DAX measures (Revenue, Profit, Margin)
    4- Dimension tables set as reference queries no data duplication
    5- Cleaner, more scalable model following professional BI standards

# Recommendations:
    1- merge complementary products such as Computers with Accessories to increase AOV 
    2- Asia is a promising market specially China
    3- We lose our market in North Amerca so we have to do some marketing and sales to high our Revenue

# Limitations & Future Improvements:
    1- Dataset contains 15K rows which limits statistical significance
    2- limited dates to track patterns
    3- no customer data available so I can't analyze on what product sold why
    4- no data about which Items ordered together to try increse AOV based on data
