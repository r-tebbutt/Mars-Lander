-------------------------------------------
		DISCLAIMER
-------------------------------------------

Files 'lander.h' and 'lander_graphics.cpp' of this project were written by Gabor Csanyi and Andrew Gee as part of 
work to be set on the engineering degree course at the University of Cambridge.
'lander.cpp' was intended to be filled in by the student.

I have only written the code in the 'lander.cpp' file myself. The source code has not been modified.

While not set as compulsory work on my course (Natural Sciences), I completed the project as a fun way to
explore some computational physics.

-------------------------------------------


The Mars Lander project involved using Euler and Verlet integration to calculate the numerical dynamics
of a mars lander as tiem evolved, from different initial conditions. Altering the initial conditions
determined the path of the lander, be it circular or elliptical, stable or decaying orbit or just a 
vertical descent.
The Euler and Verlet dynamics would create some discrepancies in trajectory, as Euler dynamics are less 
accurate and add energy to the system, which is not the case for Verlet.

Once the lander moved according to the computed laws of physics, an auto pilot was designed using some basic control
theory to safely land the lander in vertical descent scenarios 1 and 5, which was done successfully.
The target was a linearly decreasing velocity once the auto pilot system was activated, and this was achieved 
aslong as the velocity was sufficiently low at the activation altitude to make this feasible.

