This is a grow room temperature control blueprint for HA
What is unique about this script is that is sets the temperature of the grow room dependent on light state.
Higher temp during the day and lower temp during the night.
You can set these to wherever you like.
Setpoint/hysteresis is the difference between min-max temps.

It requires these helpers in order work function.
- input_number.grow_absolute_max_temp
- input_number.grow_absolute_minimum_temp
- input_number.grow_day_temperature_high
- input_number.grow_day_temperature_low
- input_number.grow_night_temperature_high
- input_number.grow_night_temperature_low

It requires these entities as switches
- your-light-switch
- your-heater-switch
- your-temperature-sensor

This document is still being written
