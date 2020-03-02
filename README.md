# Flight_Analysis

Landing data from 950 commercial flights.
Landing overrun is problem for most flight landing operations. 
We identify key factors affecting the landing distance of commercial flights. 

Data Dictionary:
Aircraft: The make of an aircraft (Boeing or Airbus).

Duration (in minutes): Flight duration between taking off and landing. The duration of a normal flight should always be greater than 40min.

No_pasg: The number of passengers in a flight.

Speed_ground (in miles per hour): The ground speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.

Speed_air (in miles per hour): The air speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.

Height (in meters): The height of an aircraft when it is passing over the threshold of the runway. The landing aircraft is required to be at least 6 meters high at the threshold of the runway.

Pitch (in degrees): Pitch angle of an aircraft when it is passing over the threshold of the runway.

The goal here is to reduce the risk of landing overrun.

Concepts used in this analysis:
Linear Regression
Variable Selection
AIC/BIC
Forward Backward Selection
Logistic Regression
Multinomial Regression
Binary Classification
Poisson

