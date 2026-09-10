# A3 – [Topic]

## Objective

The objective of this assignment is to design an aluminum bar for maximum stiffness while maintaining a specified axial deflection limit. I will use parametric modeling in Fusion 360 to relate the bar's diameter, length, applied force, Young's modulus, and maximum allowable deflection. After creating the bar, I will use FEA to determine the maximum displacement and von Mises stress and compare these results to my hand calculations. Finally, I will check the stress against the aluminum yield strength to determine the factor of safety and evaluate whether the design meets the required parameters.

## Analyze


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




## Communicate

