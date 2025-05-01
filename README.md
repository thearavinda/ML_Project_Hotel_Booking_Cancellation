# **Hotel Booking Cancellation Prediction**
**Dataset source**:Kaggle

**Dataset link** :https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
# **Problem statement**
In order to solve this problem, Here use a real life hotel booking dataset to create a customer segmentation analysis in order to gain insights about the customers (and hopefully reasons why they cancel their reservation). Here i am build a classification model (including the newly created customer clusters) to predict whether or not a booking will be canceled with the highest accuracy possible.
This model will allow hotels to predict if a new booking will be canceled or not, manage their business accordingly, and increase their revenue.
# **About The Dataset**
The dataset contains 119390 rows and 32 coloumns.Our goal is to build a model able to classify a booking as canceled or not canceled.

**FEATURES:**

**Hotel :** (Resort Hotel or City Hotel)

**lead_time :** Number of days that elapsed between the entering date of the booking into the Property Management System and the arrival date. Calculated by subtracting the entering date from the arrival date.

**arrival_date_year :** Year of arrival date

**arrival_date_month :** Month of arrival date

**arrival_date_week_number :** Week number of year for arrival date

**arrival_date_day_of_month :** Day of arrival date

**stays_in_weekend_nights :** Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

**stays_in_week_nights :** Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

**adults :** Number of adults

**children :** Number of children

**babies :** Number of babies

**meal :** Type of meal booked. Categories are presented in standard hospitality meal packages **BB** - (Bed and Breakfast)
**HB**- (Half Board)
**FB**- (Full Board)
**SC**- (Self Catering)

**country :** Country of origin.`

**market_segment :** Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

**distribution_channel :** Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

**is_repeated_guest :** Value indicating if the booking name was from a repeated guest (1) or not (0)

**previous_cancellations :** Number of previous bookings that were cancelled by the customer prior to the current booking

**previous_bookings_not_canceled :** Number of previous bookings not cancelled by the customer prior to the current booking

**reserved_room_type :** Code of room type reserved. Code is presented instead of designation for anonymity reasons.

**assigned_room_type :** Code for the type of room assigned to the booking.

**booking_changes :** Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

**deposit_type :** Indication on if the customer made a deposit to guarantee the booking.

**agent :** ID of the travel agency that made the booking

**company :** ID of the company/entity that made the booking or responsible for paying the booking.

**days_in_waiting_list :** Number of days the booking was in the waiting list before it was confirmed to the customer

**customer_type :** Type of booking, assuming one of four categories

**adr :** Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

**required_car_parking_spaces :** Number of car parking spaces required by the customer

**total_of_special_requests :** Number of special requests made by the customer (e.g. twin bed or high floor)

**reservation_status :** Reservation last status, assuming one of three categories

**Canceled –** booking was canceled by the customer
**Check-Out –** customer has checked in but already departed
**No-Show –** customer did not check-in and did inform the hotel of the reason why

**reservation_status_date -** Date at which the last status was set

**TARGET**

**is_canceled**: Value indicating if the booking was canceled (1) or not (0)


