# HA-grow-temperature

## This is a grow room temperature control blueprint for HA.
What is unique about this script is that this script monitors the light switch and sets the temperature of the grow room accordingly.  
Higher temp during the day and lower temp during the night.   
Setpoint/hysteresis is the difference between min-max temps.   
This script also has sanity checking so that if you set the minimum temp above the max temp it will shut down the heater.   


## helpers

- input_number.grow_absolute_max_temp
- input_number.grow_absolute_minimum_temp
- input_number.grow_day_temperature_high
- input_number.grow_day_temperature_low
- input_number.grow_night_temperature_high
- input_number.grow_night_temperature_low

## switch/sensor entities

- your-light-switch
- your-heater-switch
- your-temperature-sensor
