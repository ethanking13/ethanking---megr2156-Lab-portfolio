# A5 – [Design a Snap Fit]

For this assignment, I was tasked with parametrically designing a two-component assembly that would snap fit together using SolidWorks parameters and constraints. I used PLA material properties, a safety factor of 3.5, and beam equations to determine the dimensions needed for the flexure while ensuring the design could withstand the required loads. After designing the components in SolidWorks, I 3D printed and tested them, then evaluated the results and made any necessary improvements.


# Modeling

<img width="1438" height="973" alt="IMG_0383" src="https://github.com/user-attachments/assets/c93e5b26-9a12-4a01-a61b-8aa2fd47e7d2" />


## Given Data

The following material properties, loads, and initial dimensions were selected for the snap-fit flexure design.

| Parameter                     |       Value |
| ----------------------------- | ----------: |
| Young's Modulus, \(E\)        |     2.7 GPa |
| Young's Modulus, \(E\)        | 391,600 psi |
| Yield Strength, \(S_y\)       |    3600 psi |
| Safety Factor                 |         3.5 |
| Transverse Load, \(P\)        |    0.25 lbf |
| Axial Load, \(P_a\)           |       5 lbf |
| Initial Width, \(b\)          |     0.10 in |
| Initial Thickness, \(h\)      |     0.20 in |
| Target Deflection, \(\delta\) |     0.04 in |


The initial dimensions and loading conditions were selected based on the requirements of the snap-fit design and the available range given in the assignment. A transverse load of 0.25 lbf and an axial load of 5 lbf were chosen because they are within the required loading ranges. The flexure was initially designed with a width of 0.10 in and a thickness of 0.20 in to provide enough material for the part while still allowing the flexure to bend. A target deflection of 0.04 in was selected to provide the flexing needed for the two components to snap together. Using these values, the cantilever beam equation was used to determine the required flexure length, and the resulting stresses were checked against the allowable stress using a safety factor of 3.5.

## Calculations

<img width="1249" height="856" alt="IMG_0382" src="https://github.com/user-attachments/assets/a2d5cd3d-bd5f-4820-91f6-bb5f41e2f8df" />


# Parametric Design

# 3D Printing and Testing

