
## Objective

The objective of this assignment is to design an aluminum bar for maximum stiffness while maintaining a specified axial deflection limit. I will use parametric modeling in Fusion 360 to relate the bar's diameter, length, applied force, Young's modulus, and maximum allowable deflection. After creating the bar, I will use FEA to determine the maximum displacement and von Mises stress and compare these results to my hand calculations. Finally, I will check the stress against the aluminum yield strength to determine the factor of safety and evaluate whether the design meets the required parameters.

## Analyze

I chose 2 inches for my cylinder diameter, using that diameter and all the other measurements I was given I calculated the length 

<img width="1000" height="400" alt="IMG_1691" src="https://github.com/user-attachments/assets/1f36956d-dd79-4523-b574-f6f969255e11" />


## CAD - Fusion

I start the design by setting my parameters

<img width="600" height="250" alt="Screenshot 2026-09-10 023527" src="https://github.com/user-attachments/assets/f7ed6f56-9095-4023-8899-ab84b2e3dbf4" />


Using those parameters I create my cylinder

<img width="800" height="700" alt="Screenshot 2026-09-10 023707" src="https://github.com/user-attachments/assets/ec684956-27bf-4e7b-ae53-420a4fa5bf59" />

<img width="800" height="600" alt="Screenshot 2026-09-10 023916" src="https://github.com/user-attachments/assets/99f6cd74-6230-438f-9af6-cf099511a46c" />


After the cylinder is created I change the material to aluminum, though the Young's Modulus is different than my hand calculation one, it isn't by a lot

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/481dc029-91fa-4b62-8ac6-9b15a905e96b" />



## Deflection and Von Mises

I created the study by locking one side of the cylinder and applying a 400lb force to the other and then generated the results.

The deflection curve was a lot higher than my hand calculation almost doubling it.

<img width="1000" height="300" alt="image" src="https://github.com/user-attachments/assets/76cd9135-965e-45a7-8443-da88e31bd281" />

My von Mises results show that it is about 336 psi or .336 ksi, which is under the 40 ksi limit thus passing.

<img width="1000" height="300" alt="image" src="https://github.com/user-attachments/assets/5783f0b0-03fa-4f6d-b4a1-1d3c89affe11" />

Safety Factor = 40 ksi/ .336 ksi, which gives us a safety factor of about 119



## Design Reflection

a)
There was a meaningful discrepancy with my hand-calculated result compared to my simulated result. With a percent difference of 88.9%
% Difference= (∣0.017−0.009∣/.009)*(100) = 88.9%
	​

This is a meaningful discrepancy. A likely source is the boundary conditions used in the FEA compared with the assumptions made in the hand calculation. The hand calculation assumes a uniform bar under ideal axial tension, with uniform stress and deformation along the length. For this design, I would trust the FEA result more because it models the actual geometry, fixture, and loading conditions rather than relying entirely on the ideal assumptions of the axial-deflection equation.

b)The estimated peak stress at the pin hole is approximately 0.254 ksi, which is well below the aluminum yield strength of 40 ksi. Therefore, the bar would still pass the safety factor requirement even with the  hole.

## Parameter change

I changed the applied force to 300 lbf and diameter to .25 in. 
I believe the length will get shorter. 

After inputting the new values Fusion automatically did the calculation and supported my hypothesis that the length would get shorter.
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/e9789058-3c63-4c0e-94c3-4076c0e61b9f" />



## Lessons Learned

I learned a lot from this assignment, particularly about creating simulations and using parametric design to develop an engineering model. I made a few mistakes along the way, including entering incorrect parameter equations and forgetting to convert the force from newtons (N) to pounds-force (lbf). These mistakes helped me better understand the importance of checking units, verifying equations, and reviewing parameter relationships before running a simulation.

This assignment took me about 5 hours to complete
