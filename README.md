# Binary-Star-System-Analysis
This assignment was given by Krittika Club of IITB as a task in their application form for Summer Projects. They provided us with the Doppler shift data (download here: https://drive.google.com/file/d/1sThNaS5kgOKpCjhgXIvo3LcOflslTKaH/view?usp=sharing) in the Balmer line of two stars in a binary star system orbiting about a common centre of mass. 

Following points were given for the problem:

1. Cosmological redshift can be ignored.
2. The orbital plane of the system is assumed to be parallel to the line of sight.
3. The orbit is circular, and the whole system (or the centre of mass) is moving radially towards/away from us.

We were to find the Period of Revolution and mass of both the stars.

# My Approach to the Problem
1. Using the redshift data, the velocities (recessional velocity of the COM + the radial component of the orbital velocity) of the stars is being calculated. The redshift data is only able to give the radial component of orbital velocity because the plane of the Binary System is parallel to the line of sight.

2. The scatter plots between velocity and time for both the stars are then plotted. As expected, the curves resemble two intersecting sine curves. The points where the orbital velocity vector is perpendicular to the line of sight, the redshift due to stars is zero and the curve must show the recessional velocity at this point. Both the stars must exhibit this at the same time as they have the same period and hence the velocity at the line passing through the intersection points of the two sine waves should give the recessional velocity. 

3. The velocity at all intersection points are not same, but very close and hence a mean of these velocities is calculated to give a good approximation of the recessional velocity of the COM. 

4. The recessional velocity found in this manner is then subtracted from velocities found earlier and then plotted. This leaves us with only the radial component of the orbital velocity of both the stars. 

5. The Sine curve fitting is done and both the curves now oscillate about the line passing through zero indicating zero redshifts at the point of intersection. 

6. The peaks of these waves are the points where the orbital velocity vector is parallel to the line of sight and hence the amplitude will give us the orbital velocity. The time period is calculated from the curve and this information is then used to calculate mass.

# [Derivation](https://github.com/SimranJoharle/Binary-Star-System-Analysis/blob/master/Derivation.pdf)
# [Code](https://github.com/SimranJoharle/Binary-Star-System-Analysis/blob/master/Analysis%20of%20a%20Binary%20System.ipynb)
