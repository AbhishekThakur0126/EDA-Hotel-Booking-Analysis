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
1. How Many Booking Were Cancelled?
2. What is the booking ratio between Resort Hotel and City Hotel?
3. What is the percentage of booking for each year?
4. Which is the most busy month for hotel?
5. From which country most guest come?
6. How Long People Stay in the hotel?
7. Which was the most booked accommodation type (Single, Couple, Family)?

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
5. Most guests tend to stay in the hotels for 1-4 days.
6. City Hotel has a higher guest retention rate compared to other hotels.
7. Around one-fourth of the total bookings get canceled, with City Hotel having the highest cancellation rate.
8. New guests tend to cancel bookings more frequently than repeat customers.
9. Factors like lead time, number of days in the waiting list, or the assignation of reserved rooms to customers do not significantly affect the cancellation of bookings.
10. Corporate guests have the highest percentage of repeat bookings, while TA/TO has the lowest. In the case of canceled bookings, TA/TO has the highest percentage, while Corporate has the lowest.
11. The length of stay tends to decrease as ADR increases, probably to reduce costs.

**Sources** This project is part of AlmaBetter Curriculum.
