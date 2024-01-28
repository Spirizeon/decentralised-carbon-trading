# Renewable energy production scope
This Python script is designed to predict the amount of renewable energy that can be produced based on occupancy and temperature data.
The code uses a dataset named Energy_consumption.csv from Kaggle's input folder.

## Target variable
+ 'RenewableEnergy' is presumably the amount of renewable energy that could theoretically be generated given the occupancy and temperature.

## Features
The features being targeted in this script are 'Occupancy' and 'Temperature'. These are selected as inputs for the machine learning model because they are assumed to have a significant impact on the amount of renewable energy that can be produced.

+ 'Occupancy' likely refers to the number of people present in a certain location or building. 
+ 'Temperature' refers to the temperature of the building in degree Celsius

# Analysis: It is predicted that
+ scope of production slowly increases till 10
+ rate increase till near 14 KWh, then starts decreasing
+ rate increases but not as fast as before at a steady rate 
+ rate keeps increasing as temperature increases

## Possible method that can help produce renewable energy
Heat Recovery Ventilation (HRV): HRV is an energy recovery ventilation system that works between two air sources at different temperatures. It recovers the residual heat in the exhaust gas, preheating the fresh air introduced into the air conditioning system 

### Sources:
+ https://en.wikipedia.org/wiki/Renewable_heat
+ https://www.carrier.com/residential/en/us/products/air-conditioners/how-do-air-conditioners-work/
