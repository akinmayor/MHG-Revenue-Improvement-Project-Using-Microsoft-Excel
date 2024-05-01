# MHG-Revenue-Improvement-Project-Using-Microsoft-Excel

## Project Overview

Maven Hotel Group (MHG) is a fictional Portuguese hotel chain facing challenges with increasing cancellation rates, leading to significant revenue loss. This project aims to quantify the impact of cancellations on revenue and identify strategies to improve revenue performance. The primary objective is to build an Explanatory Dashboard to visualize insights effectively and provide actionable recommendations.

## Problem Statement

MHG has experienced spikes in cancellation rates over the past three years, resulting in substantial revenue loss. The lack of visibility into the reasons for cancellations makes it challenging to implement targeted strategies to mitigate revenue loss.

## Objectives

1. Quantify the impact of cancellations on MHG's revenue.
2. Identify key factors contributing to cancellation rates.
3. Develop an Explanatory Dashboard to visualize insights effectively.
4. Provide actionable recommendations to improve revenue based on data analysis findings.

## Data Source : Hotel Booking Demand.

## Dimensions & Measures :

1. Dimensions : Booking ID, Hotel, Booking/Arrival Date, Distribution Channel, Customer Type, Country, Deposit Type, Status, Status Update, Cancelled (0/1)
2. Measures : Lead Time, Nights, Guests, Revenue, Loss

## Excel Concepts Covered :

- Pivot Charts & Tables.
- Conditional Number formatting.
- Explanatory Dashboard with Problems & Recommendations detail.
- Combining dashboard objects and pasting same as an image.
- Partial Pivot Charts
- Experiment with chart elements and layouts
- Usage of color and style strategically
- Formatting options
- Understanding & usage of a secondary axis

## Tools Used

- **Microsoft Excel:** Data analysis and dashboard creation.
- **GitHub:** Version control and collaboration on project documentation.

### Dashboard Design Considerations

- **Visual Effectiveness:** Intuitive visualizations to convey insights clearly.
- **Color Consistency:** Applied consistent color schemes to highlight key metrics and trends.
- **Dashboard Layout:** Organized content logically to facilitate easy navigation.
- **Textual Clarity:** Concise explanations and annotations to enhance interpretability.

## Data Analysis Findings

### Analysis of Cancellation Rates and Average Daily Rates (ADR) for our Resort Hotels

![Cancellation Rates and ADR](https://github.com/akinmayor/MHG-Revenue-Improvement-Project-Using-Microsoft-Excel/assets/77463041/4f2fa546-0a85-4833-91bb-9def0d858bf1)

#### 1. Yearly Trends:
- **2015:** Cancellation rates range from 17% to 35%, with the highest rate in September. ADR varies between $46 and $156.
- **2016:** Cancellation rates peak in July and August, reaching 32% and 34% respectively. ADR also peaks during these months, suggesting a potential correlation between cancellation rates and ADR.
- **2017:** Both cancellation rates and ADR continue to exhibit similar trends, with peak cancellation rates in June, July, and August.

#### 2. Seasonal Patterns:
- **Summer Peaks:** Cancellation rates tend to spike during the summer months (June, July, and August), coinciding with higher ADR. This could indicate higher demand during these months, leading to more cancellations.
- **Off-Peak Seasons:** Cancellation rates decrease during off-peak months (e.g., November to March), corresponding to lower ADR. Lower demand during these periods may contribute to fewer cancellations.

#### 3. Correlation Analysis:
- There seems to be a correlation between cancellation rates and ADR, especially during peak months. Higher ADR could potentially lead to higher cancellation rates as guests may be more selective or have higher expectations during peak seasons.

#### 4. Impact on Revenue:
- High cancellation rates during peak months significantly impact revenue, as these months coincide with higher ADR. Implementing strategies to reduce cancellations during peak seasons will help mitigate revenue loss.
------
To further analyze the provided revenue data for 2016 and understand the impact of high cancellations on revenue loss, let's break down the revenue and revenue loss figures:

### Revenue and Revenue Loss Analysis for 2016(Resort Hotels)
![Revenue and loss](https://github.com/akinmayor/MHG-Revenue-Improvement-Project-Using-Microsoft-Excel/assets/77463041/c211ecf1-7aa3-4426-bb2f-7915a060c649)

#### 1. Monthly Revenue:
- **January to June:** Revenue steadily increases from $91,089 in January to $534,232 in June, indicating peak seasonality during this period.
- **July and August:** Revenue peaks during these months, reaching $780,925 in July and $1,005,690 in August, corresponding to high demand and ADR.
- **September to December:** Revenue gradually decreases towards the end of the year, with lower figures compared to the peak summer months.

#### 2. Revenue Loss due to Cancellations:
- **January to June:** Revenue losses due to cancellations increase as revenue grows, indicating a proportional impact of cancellations on revenue.
- **July and August:** Revenue loss reaches its peak during these months, with -$398,143 in July and -$593,037 in August. This highlights the significant impact of high cancellations during peak season months.
- **September to December:** Revenue loss decreases towards the end of the year, corresponding to the decline in revenue and potentially lower cancellation rates during off-peak months.

#### 3. Total Revenue Loss:
- **High Impact of Peak Months:** The combined revenue loss during July and August alone amounts to nearly $1,000,000, indicating the substantial impact of cancellations during these peak season months.
------
Based on the provided data for 2016, it appears that lead time is a significant factor influencing cancellation rates and revenue loss. Reservations booked more than one month in advance have a considerably higher cancellation rate compared to those booked within 30 days of the stay. Here's a breakdown of the analysis:

### Lead Time Analysis for 2016
![Oppotunity](https://github.com/akinmayor/MHG-Revenue-Improvement-Project-Using-Microsoft-Excel/assets/77463041/ba145dd2-0f0c-4533-a423-79b20f35622f)

#### 1. The Problem:
- **Reservations with Lead Time > 30 days:** These reservations contribute significantly to revenue loss, with 859 cancellations recorded in 2016.
- **Cause of Revenue Loss:** The majority of revenue loss is attributed to reservations booked more than one month in advance, indicating potential uncertainty or changes in plans among guests booking well in advance.

#### 2. The Opportunity:
- **Overbooking Same-Month Reservations:** Reservations booked within 30 days of the stay have a lower cancellation rate (20%) compared to those booked more than 30 days in advance (38%).
- **Revenue Potential:** Same-month reservations also tend to have a higher average daily rate ($191), suggesting an opportunity to capitalize on this segment of bookings.
------
### Recommendations:

1. **Dynamic Pricing Strategy:** Implement dynamic pricing strategies to adjust ADR based on demand fluctuations. Offer competitive pricing during off-peak seasons to attract bookings and mitigate revenue loss during peak months.

2. **Cancellation Policies:** Review and revise cancellation policies to incentivize non-refundable bookings or offer flexible cancellation options for reservations booked well in advance (>30 days). Consider implementing penalties or fees for cancellations beyond a certain lead time.

3. **Customer Engagement:** Enhance customer engagement through targeted marketing campaigns or loyalty programs to encourage direct bookings. Offer exclusive deals or incentives for same-month bookings to capitalize on the segment's lower cancellation rates and higher ADR.

4. **Dynamic Inventory Management:** Overbook same-month reservations during peak seasons to replace the bookings made in advance, which are likely to be canceled, with bookings that have a lesser risk of cancellation. These same-month bookings can be sold at a higher average price, maximizing revenue potential.

### Conclusion:
The analysis reveals key insights into the factors influencing cancellation rates and revenue loss for MHG. By implementing the recommended strategies, MHG can optimize revenue performance, mitigate the impact of cancellations, and enhance overall business profitability. By leveraging dynamic pricing, flexible cancellation policies, targeted marketing, and dynamic inventory management, MHG can adapt to changing market conditions and maximize revenue potential.
