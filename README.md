# Revenue-insights-in-hospitality-domain

![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Revenue%20Insights%20img.png)


___

## Introduction
A significant participant in the luxury and business hotel industries in India, AtliQ Grands is struggling to maintain revenue and market share as a result of heightened competition and internal inefficiencies. The managing director has started a deliberate move towards the integration of business and data intelligence in order to solve this. In order to use historical data for insights and decision-making, the revenue management team has partnered with a third-party data analytics service provider. The mission assigned to a data analyst is to create a dashboard that offers practical information with the goal of helping AtliQ Grands maximise revenue and recover market share in the cutthroat hotel industry.

___
## Problem Statement

There is a deficiency in data-driven decision-making, AtliQ Grands is facing substantial hurdles in sustaining its market share and revenue in the luxury/business hotel segment. The use of data analytics by competitors to make competitive threats, poor decision-making procedures, poor customer experience management, subpar revenue optimization, and inefficient operational procedures are some of the main problems. To reestablish market competitiveness and revenue growth, AtliQ Grands must employ data analytics and business intelligence to address these issues.

___

# Client's Requirements For Dashboard



The dashboard framework specifications provided by the client include details on the layout, visual components, color schemes, typefaces, and interactivity. Furthermore, in order to track business success and strategic advancement, they can have established key performance indicators and other measures. Following these recommendations guarantees that the dashboard lives up to customer expectations and provides useful information for well-informed decision-making.

   ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20rules%20by%20Client%2001.png)
   ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20rules%20by%20Client%2002.png)

___

 ## Skills and Concepts Demonstrated
  - Data visualization
  - SQL
  - Data Transformation
  - Data Cleaning
  - Power BI
  - Power Query Editor
  - Modelling
  - Excel
  - Data Analysis
  ____

  # Helper Document 

  
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Helper%20Document%20-%20hospitality%2002.png)  
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Helper%20Document%20-%20hospitality%2001.png)
  _____

  ## Data Collection

  In order to gather information for this project, data from AtliQ Grands hardware systems, such as property management systems (PMS), had to be scraped in order to gain insightful knowledge about many operational facets. This contains data on reservations, lodging occupancy, visitor preferences, and other pertinent variables. We guarantee the timeliness and accuracy of the information by obtaining it straight from the hotel's own systems, which allows for more accurate analysis and useful insights. Furthermore, data scraping provides an all-encompassing perspective of operational performance across many properties, supporting a comprehensive method of strategic planning and decision-making for improved client experiences and revenue optimization.
 
___
  ## Data Cleaning



One of the most important steps in getting the gathered datasets ready for analysis is data cleaning. To maintain the correctness and integrity of the data, a procedure of finding and fixing errors, missing numbers, and inconsistencies must be followed. The AtliQ Grands dataset was thoroughly cleaned, with duplicate entries eliminated, data formats standardized, and missing values imputation performed using suitable methods such as mean imputation or interpolation. In order to keep outliers from distorting analysis results, they were also found and either fixed or marked for more research. Through thorough dataset cleaning, we make sure that analyses that come after are founded on solid, trustworthy data, which strengthens the validity and reliability of the conclusions drawn from the data analysis process.


____

# Meta Data

1. dim_date
2. dim_hotels
3. dim_rooms
4. fact_aggregated_bookings
5. fact_bookings


Column Description for dim_date:
1. date: This column represents the dates present in May, June and July.
2. mmm yy: This column represents the date in the format of mmm yy (monthname year).
3. week no: This column represents the unique week number for that particular date.
4. day_type: This column represents whether the given day is a Weekend or Weekday.



Column Description for dim_hotels:
1. property_id: This column represents the Unique ID for each of the hotels.
2. property_name: This column represents the name of each hotel.
3. category: This column determines which class[Luxury, Business] a particular hotel/property belongs to. 
4. city: This column represents where the particular hotel/property resides.



Column Description for dim_rooms:
1. room_id: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
2. room_class: This column represents to which class[Standard, Elite, Premium, Presidential] particular room type belongs.


Column Description for fact_aggregated_bookings:
1. property_id: This column represents the Unique ID for each of the hotels.
2. check_in_date: This column represents all the check_in_dates of the customers.
3. room_category: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
4. successful_bookings: This column represents all the successful room bookings that happen for a particular room type in that hotel on that particular date.
5. capacity: This column represents the maximum count of rooms available for a particular room type in that hotel on that particular date.



Column Description for fact_bookings:
1. booking_id: This column represents the Unique Booking ID for each customer when they booked their rooms.
2. property_id: This column represents the Unique ID for each of the hotels
3. booking_date: This column represents the date on which the customer booked their rooms.
4. check_in_date: This column represents the date on which the customer check-in(entered) at the hotel.
5. check_out_date: This column represents the date on which the customer check-out(left) of the hotel.
6. no_guests: This column represents the number of guests who stayed in a particular room in that hotel.
7. room_category: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
8. booking_platform: This column represents in which way the customer booked his room.
9. ratings_given: This column represents the ratings given by the customer for hotel services.
10. booking_status: This column represents whether the customer cancelled his booking[Cancelled], successfully stayed in the hotel[Checked Out] or booked his room but not stayed in the hotel[No show].
11. revenue_generated: This column represents the amount of money generated by the hotel from a particular customer.
12. revenue_realized: This column represents the final amount of money that goes to the hotel based on booking status. If the booking status is cancelled, then 40% of the revenue generated is deducted and the remaining is refunded to the customer. If the booking status is Checked Out/No Show, then the full revenue generated will go to hotels.





___
  ## End Result

  In my professional role, I carefully created a solid data model and carefully designed an advanced dashboard for the project. I streamlined the information flow and improved data visualization by carefully analyzing and implementing my plan. My job was to convert complex data into understandable visual representations so that the organization could make well-informed decisions. 
  ___
  

  ## Dashboard
___
  ## 01 REVENUE INSIGHTS IN THE HOSPITALITY DOMAIN MAIN DASHBOARD
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2001.png)
  _____
  ## 02 REVENUE TREND BY WEEK
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2002.png)
  ___
  ## 03 REVPAR BY WEEK NO AND DAY TYPE
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2003.png)
 
  ___
  # 04 
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2005.png)
  ___
  # 05 PROPERTY BY KEY METRICS
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2006.png)
  ___
 
  
   # 06 ADR BY WEEK NO
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2011.png)
  ___
  # 07 DSRN BY WEEK NO
  
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2009.png)
___
# 08 OCCUPANCY PERCENTAGE BY WEEK NO AND DAY TYPE 
  ![](https://github.com/Danush-US/Revenue-insights-in-hospitality-domain/blob/main/Dashboard%20Img%2010.png)
  ___

  
  
  
  

THE END
