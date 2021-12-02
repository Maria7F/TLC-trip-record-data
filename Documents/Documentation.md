# TLC Trip Record Data

## Abstract
The pupouse of this project is to predict the fare ammount of the trip with ~4,000,000 taxi rides, using linear regression algoritm. I worked with data provided by [TLC Trip Record Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page), 



## Design
The yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP). The trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.

## Used Data
The dataset contains ~4,000,000 taxi rides with 18 features for each, 13 of which are float64, 3 are int64 and 2 are objects.
* vendor_id - a code indicating the provider associated with the trip record
* pickup_datetime - date and time when the meter was engaged
* dropoff_datetime - date and time when the meter was disengaged
* passenger_count - the number of passengers in the vehicle (driver entered value)
* trip_distance - The elapsed trip distance in miles reported by the taximeter.
* RatecodeID -The final rate code in effect at the end of the trip.
1= Standard rate
2=JFK
3= Newark
4= Nassau or Westchester 5=Negotiated fare 6=Group ride
* PULocationID - Pick up zone
* DOLocationID - Drop off zone

## Algorithms

1. Feature engineering to extract the peak hours and the car type either it's a van or regular taxi for 4 passengers
2. Hot-one encoding for the Rate code ID
3. Converting dates to datetime type
4. Extract the Day and Hours from the dates
5. Linear regression model

<!-- *Models* -->
  


## Tools
*	Python and Jupyter Notebook 
*	Numpy and Pandas for data manipulation 
*	Matplotlib and Seaborn for plotting visuialization 
*	Folium for for visualizing geospatial data 
*	Sklearn for LinearRegression

## Visualization
- Line plot 
<!-- <img src="criticalFlag.png" width=500> -->

- Histograph plot
<!-- <img src="map.png" width=500> -->
