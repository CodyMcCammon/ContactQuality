# ContactQuality
A physics-based approach to representing quality of contact at the moment of impact.

This project seeks to find weaknesses/strengths in hitter/pitcher approach (attack angle, timing, spin, force, etc.) to determine the quality of contact for each pitch. From this data, trends can be found in each player's approach with the express intent of maximizing contact quality (for hitters) or minimize contact quality (for pitchers).

# Current Status: 

The primary focus right now is creating the model at a basic level. From there, I can tune the equations to include more and more dynamics. 
 * Fluid dynamics will be necessary, but I am not sure how much of the atmosphere can be accounted for outside of average wind speed and direction, humidity, and temperature. None of these are included in bat-tracking data, and the actual wind itself will be different. Each stadium creates different currents as well. 

Locating bat-tracking and pitch-tracking data. Understanding how to use it. 
* Better to do it on a pitch-by-pitch basis? Or average for swings for each type of pitch in each zone? <-- Start with the average

Generating EOM (equaions of motion) for MOI (moment of impact). 

# References:
https://baseball.physics.illinois.edu/index.html

https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/aerodynamics-of-baseball/
