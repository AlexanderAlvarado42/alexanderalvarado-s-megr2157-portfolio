# A5 – [Topic]

## Objective
The objective of this assignment was to design a component by analyzing stress and stiffness, and make sure the component is able to work.

## Analyze

## Design Parameters

- **Material:** Aluminum 6061-T6
- **Yield Strength:** $S_y = 40,000$ psi
- **Elastic Modulus:** $E = 10 \times 10^6$ psi
- **Applied Load:** $F = 600$ lbf
- **Total Load:** $W = 2F = 1200$ lbf
- **Safety Factor:** $SF = 4$
- **Allowable Stress:** $\sigma_{allow} = 10,000$ psi
- **Maximum Deflection:** $\delta_{max} = 0.005$ in

### T-Beam Dimensions

- $a = 0.498$ in
- $b = 0.9992$ in
- $c = 1.499$ in

### Assumptions

- Direct shear failure is neglected.
- Shear deflection is neglected.
- Loading is symmetric.
- Material remains elastic.
- Stress concentrations are neglected.
- Reactions from each feature are carried into the next feature.

## Calculating Dimensions
<img width="2000" height="1500" alt="IMG_1784" src="https://github.com/user-attachments/assets/e3297388-ea75-4e21-b1d1-57e920c3b0f0" />



<img width="2000" height="1500" alt="IMG_1785" src="https://github.com/user-attachments/assets/0795d03f-a6b8-4bbf-b7a7-8c6a27d8a42d" />



<img width="2000" height="1500" alt="IMG_1786" src="https://github.com/user-attachments/assets/1ee5d255-c493-4964-8d73-a341e5e4fe92" />



<img width="2000" height="1500" alt="IMG_1787" src="https://github.com/user-attachments/assets/b5294f88-9269-48ba-a44a-bebb316e4aaa" />



<img width="2000" height="1500" alt="IMG_1788" src="https://github.com/user-attachments/assets/1a39a2a8-f55d-4af6-b316-e0e1c2bd3d3e" />




## Lessons Learned

- **Error Propagation:** An error in an earlier feature could affect the loads and dimensions of later features. Checking each reaction force helped prevent errors from carrying forward.

- **Assumption Sensitivity:** Neglecting shear deflection simplified the analysis. Including it could increase the required dimensions, especially for thinner features.

- **Stress vs. Stiffness:** A part can be stiff enough but still fail from excessive stress. Both analyses were needed to determine the final dimensions.

- **Importance of Geometry:** The geometry of each feature determined which equation was appropriate. Choosing the correct model was just as important as solving the equations correctly.

