> ##### The goals is to turn data into information and information into insight :+1: :metal:


# **BANGLORE-CABS-DATA-ANALYSIS**

## DATA-DESCRIPTON :

* id - booking ID
* user_id - the ID of the customer (based on mobile number)
* vehicle_model_id - vehicle model type.
* package_id - type of package 
  * (1=4hrs & 40kms, 2=8hrs & 80kms, 3=6hrs & 60kms, 4= 10hrs & 100kms, 5=5hrs & 50kms, 6=3hrs & 30kms, 7=12hrs & 120kms)
* travel_type_id - type of travel 
  * (1=long distance, 2= point to point, 3= hourly rental).
* from_area_id - unique identifier of area. Applicable only for point-to-point travel and packages
* to_area_id - unique identifier of area. Applicable only for point-to-point travel
* from_city_id - unique identifier of city
* to_city_id - unique identifier of city (only for intercity)
* from_date - time stamp of requested trip start
* to_date - time stamp of trip end
* online_booking - if booking was done on desktop website
* mobile_site_booking - if booking was done on mobile website
* booking_created - time stamp of booking
* from_lat - latitude of from area
* from_long - longitude of from area
* to_lat - latitude of to area
* to_long - longitude of to area
* Car_Cancellation - whether the booking was cancelled (1) or not (0) due to unavailability of a car.


### TASK :
The biggest challenge is to increase the utilization rate of their cabs. However, the demand keeps fluctuating based on the area, time of day, etc. Your task is to device a geo-surge strategy that would help them incentivize their drivers. Identify what areas and at what times get most bookings and how would you increase the price in those areas in order to meet the demand.
More than any other task, it will be critical for you to get a deep understanding of the dataset, the business and how you can help them.
Brownie points​ if you share a recommendation or strategy backed by data that helps them reduce cancellation, increase revenue or reduce costs.
