## Revenue-Insights-Hospitality-

## Project Overview

Revenue Insights in the hospitality domain help businesses track and optimize their income. By analyzing data from bookings, customer behavior, and seasonal trends, these insights reveal patterns that can improve pricing, enhance marketing strategies, and increase profits.

[Live Report Link](https://project.novypro.com/oCuMJ5)

# 𝐓𝐞𝐜𝐡 𝐬𝐤𝐢𝐥𝐥𝐬 𝐈 𝐚𝐜𝐪𝐮𝐢𝐫𝐞𝐝 𝐦𝐞𝐧𝐭𝐢𝐨𝐧𝐞𝐝: 

- PowerBI Desktop
- Excel
- DAX language
- Referred Project charter file

# 𝐏𝐨𝐰𝐞𝐫𝐁𝐈 𝐓𝐞𝐜𝐡𝐧𝐢𝐪𝐮𝐞𝐬:

- Creating calculated columns
- Creating measures using the DAX language
- Data Modelling
- Creating date tables using M language
- Using KPI indicators
- Conditional formatting of the values in visuals
- Techniques of Data Validation
- PowerBI services
- Publishing reports to the PowerBI services


## Understanding the Dataset for Analysis
Before jumping into the analysis, it's important to understand the available data to ensure that decisions are well-informed and the right techniques are used. Here's an explanation of the key tables and metrics:

Dimension Tables (Static Information):
- dim_date: Contains information about dates, such as year, month, day, and other time-related attributes.
- dim_hotels: Holds details about each hotel, such as its name, location, and amenities.
- dim_rooms: Includes data about different room types, room numbers, and their respective capacities.
    
Fact Tables (Transactional Data):
- fact_aggregated_bookings: Summarizes bookings, including the total number of rooms booked, cancellation rates, and revenue generated across various time periods.
- fact_bookings: Contains detailed booking data, such as guest names, check-in/check-out dates, room types, and payment details.

Other Important Metrics:
- Revenue: The total income generated from bookings and services.
- Total Bookings: The overall number of bookings made.
- Total Capacity: The total number of rooms available for booking.
- Total Successful Bookings: Bookings that were completed successfully without cancellations.
- Occupancy %: The percentage of available rooms that were occupied.
- Average Rating: The average guest rating or feedback score for the hotel or specific rooms.
- Number of Days: The number of days in a specific period (e.g., month or year).
- Total Cancelled Bookings: The total number of bookings that were cancelled.
- Cancellation %: The percentage of bookings that were cancelled.
- Total Checked Out: The total number of guests who checked out of the hotel.
- Total No-Show Bookings: Bookings where guests didn’t show up.
- No-Show Rate %: The percentage of bookings where the guest didn’t show up.
- Booking % by Platform: The distribution of bookings made via different platforms (e.g., website, mobile app).
- Booking % by Room Class: The percentage of bookings by room type (e.g., standard, deluxe).
- ADR (Average Daily Rate): The average revenue earned per booked room per day.
- Realisation %: The percentage of booked rooms actually sold at full price or at a discounted rate.
- RevPAR (Revenue Per Available Room): A key performance indicator that shows how well the hotel is filling its available rooms and generating revenue.
- DBRN (Daily Booked Room Nights): The total number of room nights sold across all rooms on a given day.
- DSRN (Daily Sellable Room Nights): The total number of room nights available to be sold.
- DURN (Daily Utilized Room Nights): The number of room nights that were actually occupied on a specific day.
- Revenue WoW Change %: The week-over-week change in total revenue.
- Occupancy WoW Change %: The week-over-week change in occupancy rate.
- ADR WoW Change %: The week-over-week change in the average daily rate.
- RevPAR WoW Change %: The week-over-week change in revenue per available room.
- Realization WoW Change %: The week-over-week change in the realization percentage of revenue.
- DSRN WoW Change %: The week-over-week change in daily sellable room nights.

## Data Model

In data analysis and reporting, data modeling is essential as it serves as the foundation for creating accurate and efficient reports. A strong data model ensures that the visuals you build are based on well-structured, reliable data. Without good data modeling, the performance and functionality of your reports can suffer.

To make sure our reports run smoothly, we follow best practices in data modeling. These practices help ensure data is organized and easy to work with, improving both performance and usability. For this project, we’ve implemented the Snowflake Schema data modeling method, which helps break down data into smaller, more manageable pieces and minimizes redundancy.

By following these practices, we ensure that our reports are optimized and ready to deliver insightful, high-performing visuals.

![Project_Screenshot_2](https://github.com/user-attachments/assets/c223e1d4-69c2-4a3a-a9e7-140dcc8c0bc2)

and you can check out full Report here: 
