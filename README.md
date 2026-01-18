# HA-grow-temperature

<p>This is a grow room temperature control blueprint for HA.</p>
<p>What is unique about this script is that this script monitors the light switch and sets the temperature of the grow room accordingly.</p>
<p>Higher temp during the day and lower temp during the night.</p>
<p>Setpoint/hysteresis is the difference between min-max temps.</p>

<P>It requires these helpers in order work function.</P>

- input_number.grow_absolute_max_temp
- input_number.grow_absolute_minimum_temp
- input_number.grow_day_temperature_high
- input_number.grow_day_temperature_low
- input_number.grow_night_temperature_high
- input_number.grow_night_temperature_low

<p>It requires these entities as switches</p>

- your-light-switch
- your-heater-switch
- your-temperature-sensor

<p>This script also has sanity checking so that if you set the minimum temp above the max temp it will shut down the heater.</p>
This document is still being written
