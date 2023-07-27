#  EDA-Hotel-Booking-Analysis
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

We will perform exploratory data analysis with python to get insight from the data.

# Project Work Flow
* Importing Libraries
* Loading the dataset
* Exploratory data analysis
* Data Wrangling
* Data Vizualization, Storytelling & Experimenting with charts : Understand the relationships between variables
* Conclusion

# Motivation
## We have tried to answer the following Questions
Q1. How many booking were cancelled in both type of hotels?
Q2. Which Meal type is most preferable?
Q3. Which Month have highest booking?
Q4. Which type of room are most preferred?
Q5. From which country most guests are coming?
Q6. Which hotel type having highest waiting time?
Q7. Which months have cheaper booking rates?
Q8. How many number of customers repeated their bookings?
Q9. What are the number of weekend vs weekdays night bookings for resort hotels?
Q10. How does lead time affect cancellation?
Q11. How does deposit type affects cancelation?
Q12. How does ADR affect cancelation?

# Tools and Libraries Used
We have used Python 3 to its following packages:

* Numpy
* Pandas
* Matplotlib
* Seaborn
* plotly.express

# Features information:
The dataset contains features like:

1. hotel
2. is_canceled
3. lead_time
4. arrival_date_year
5. arrival_date_month
6. arrival_date_week_number
7. arrival_date_day_of_month
8. stays_in_weekend_nights
9. stays_in_week_nights
10. adults
11. children
12. babies
13. meal
14. country
15. market_segment
16. distribution_channel
17. is_repeated_guest
18. previous_cancellations
19. previous_bookings_not_canceled
20. reserved_room_type
21. assigned_room_type
22. booking_changes
23. deposit_type
24. agent
25. company
26. days_in_waiting_list
27. customer_type
28. adr
29. required_car_parking_spaces
30. total_of_special_requests
31. reservation_status
32. reservation_status_date

# Conclusion

1. City Hotel seems to be more preferred among travelers, generating more revenue and profit compared to other hotels.
2. July and August witness the highest number of bookings as compared to the rest of the months.
3. Room Type A is the most preferred choice among travelers for accommodations.
4. The majority of bookings are made from Portugal and Great Britain.
5. Majority of the hotels booked are city hotel.
6. Non-Refund policies lead to a higher cancellation rates.
7. Target months between May to Aug. Those are peak months due to the summer period.
8. Majority of the guests are from Western Europe. So target this area for advertisements.
9. Since there are very few repeated guests, focus should be on retaining the customers after their first visit.
10. Increase in lead time increases the rate of cancellation.
11. Increase in ADR also increases the rate of cancellation.
12. Customer should do their booking in during the month November to January because in these months both hotels have cheaper average daily rate.

**Sources** This project is part of AlmaBetter Curriculum.
