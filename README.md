
# HOTEL-BOOKING-ANALYSIS
Exploratory analysis Project of Hotel Booking Analysis
This is exploratory project of hotel booking analysis which contain data set of hotel bookings, information about booking city, length of stay, booking channele, when booking was made, number of adults, number of children and babies, parkig spaces etc. We will perform exploratory analysis on this data set.

# Objective
Our main objective is to perform EDA on given dataset and draw out some trend and some usefull conclusion.
 


## Data Set 
The file contain following features as column
1. hotel
2. is_canceled
3. lead_time 
4. arrival_date_year 
5. arrival_date_month
6. arrival_date_week_number
7. arrival_date_day_of_month
8. stays_in_weekend_nights
9. stays_in_weekend_nights
10. adults
11. children
12. babies
13. meal
14. country
15. market_segment
16. distribution_channel
17. is_repeated_guest
18. previous_cancellation
19. previous_bookngs_not_cancelled 
20. reserved_room_type
21. assigned_room_type
22. booking_changes
23. deposit_type
24. agent 
25. company
26. days_in_waiting_list 
27. customer_type
28. adr 
29. required_car_parking_space 
30. total_of_special_request
31. reservation_status
32. reservation_status_date 
## Tools and Libraries 
We used python as language and following Libraries of python
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborne
## Exploratory Analysis
Q1. Which type of hotel is most preferred ?    
Q2. in which month gets highest bookings?  
Q3. From Which countries most of these are customer are visiting from ?  
Q4. Which market segment gave highest bookings ?  
Q5. which room generates highest adr ?  
Q6. percentage of cancellation?  
Q7. which hotel type shows most percentage of repeat of customer ?   

## Conclusion 
1) City hotel type gets most reservation throughout the season.
2) August, July, April got most reservation in year.
3) The most of the customer came from Portugal, followed by Spain and Great Britan
4) Room type H,G,C provides good ADR
5) Thorughtout year City Hotel generates Stable adr but in case of Resort Hotel the ADR generation is high in month of August but got low in mid year.
6) More than 50% of city hotel gets cancelled and more than 30% resort hotel gets cancelled.
7) Resort Type of hotel gets high repeated customer.
8) Online TA segment gets more booking.
![image](https://user-images.githubusercontent.com/109215374/187034586-e9db96e6-b279-453d-a455-f3ec69345a3a.png)
![image](https://user-images.githubusercontent.com/109215374/187034611-fab3523e-89c0-483f-932b-2d6b059a91d4.png)
![image](https://user-images.githubusercontent.com/109215374/187034625-172801e2-39a3-43f4-a0d1-5e867443dced.png)

## Challenges 
1. The data contain to many null values 
2. There is also wrong data format in some columns like agent, children,companies etc.
3. cleaning of duplicate data 
4. choosing proper visualisation graph 
