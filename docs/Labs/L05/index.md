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

The snap-fit assembly was modeled in SolidWorks using parametric dimensions and geometric constraints. The dimensions calculated during the modeling section were used as the initial and final design values for the flexure. No dimensional changes were required during the modeling process because the original design met the required stress conditions.

## 1. Parameters Used

The main parameters used to control the flexure were:

| Parameter                     |    Value |
| ----------------------------- | -------: |
| Flexure Width, \(b\)          |  0.10 in |
| Flexure Thickness, \(h\)      |  0.20 in |
| Flexure Length, \(L\)         |  2.32 in |
| Target Deflection, \(\delta\) |  0.04 in |
| Transverse Load, \(P\)        | 0.25 lbf |
| Axial Load, \(P_a\)           |    5 lbf |
| Safety Factor                 |      3.5 |

The primary dimensions used to control the SolidWorks model were the **0.10 in width, 0.20 in thickness, and 2.32 in flexure length**.

<img width="926" height="421" alt="Screenshot 2026-09-21 232535" src="https://github.com/user-attachments/assets/2f584a9a-db50-469f-85a5-2ef4c7374326" />


## 2. Why These Parameters Were Chosen

The parameters were selected based on the requirements of the assignment and the calculations performed during the initial design stage. The 0.10 in width and 0.20 in thickness were selected as the initial cross-section of the flexure. A target deflection of 0.04 in was selected to provide the flexing needed for the snap-fit to engage. Using these dimensions and the selected transverse load, the cantilever beam equation was used to calculate a flexure length of 2.32 in.

## 3. Parameter Values

The calculated dimensions were transferred directly into SolidWorks. The flexure was modeled using a width of 0.10 in, a thickness of 0.20 in, and a length of 2.32 in. These dimensions were used as the main parameters controlling the geometry of the flexure.

## 4. Changes During the Design Process

The parameter values did not change throughout the design process. The original calculated dimensions of **0.10 in width, 0.20 in thickness, and 2.32 in length** were used in the final SolidWorks model. No iteration of the primary flexure dimensions was necessary because the calculated bending, axial, and shear stresses were below the allowable stress.

## 5. CAD Modeling Process

The two components were digitally modeled in SolidWorks using sketches, dimensions, and geometric constraints. The flexure component was created using the calculated dimensions, and the mating component was designed to interact with the flexure and create the snap-fit connection.

The CAD modeling process was documented through screenshots showing the different stages of the design.

**Figure 1:** Initial Sketch of the Flexure

Before beginning the 3D modeling process, I first created an initial sketch of the design I wanted to develop. I decided to use a standard buckle/clip-style shape as the basis for the design because it matched the type of snap-fit mechanism I was aiming to create.

<img width="725" height="747" alt="Screenshot 2026-09-21 235708" src="https://github.com/user-attachments/assets/f32cd353-8d76-400a-88f2-51182d97cb42" />

**Figure 2:** Parametric Dimensions and Constraints

After creating the initial sketch, I added the required dimensions and geometric constraints to control the shape of the component. I made the geometry symmetrical so that both sides were equal and created an exact mirrored copy from one side to the other. This helped ensure that the final component remained consistent and properly constrained.

<img width="685" height="766" alt="Screenshot 2026-09-22 001317" src="https://github.com/user-attachments/assets/09f6dda3-f220-41d1-a5af-25e9342a878b" />

**Figure 3:** Extruding the Main Component

Once the sketch was fully dimensioned and constrained, I extruded the main component to create the 3D geometry. The extrusion thickness was set to the calculated **0.20 in** dimension from the initial design calculations.

<img width="1515" height="885" alt="Screenshot 2026-09-21 235744" src="https://github.com/user-attachments/assets/aef2b6bb-f828-4c11-97e8-378ac12f7649" />

**Figure 4:** Shell/Case

Next, I designed the outer shell that the clip would attach to. The shell was made slightly larger than the clip to provide enough clearance for the component to slide completely inside while still maintaining a secure connection between the two parts.

<img width="607" height="873" alt="Screenshot 2026-09-22 162739" src="https://github.com/user-attachments/assets/7381ac53-428f-4ab2-a993-b447916056e1" />

**Figure 5:** Shell Extrusion

I then extruded the shell to a slightly greater thickness than the first component. This provided additional structural support for the shell while also creating the necessary space between the two components for the clip to slide in and out smoothly.

<img width="1545" height="946" alt="Screenshot 2026-09-22 162812" src="https://github.com/user-attachments/assets/6153558f-3dd6-4aad-badb-bd59fdf461a0" />

**Figure 6:** Component Hole

Next, I created the opening where the clip would enter and exit the shell. The cutout was designed around the geometry of the clip so that the component could move through the opening during assembly and removal.

<img width="1310" height="657" alt="Screenshot 2026-09-22 162909" src="https://github.com/user-attachments/assets/a2326f95-f916-4f1d-8708-5027455ced46" />

**Figure 7:** Shell Cutout

After creating the entrance opening, I removed material from the inside of the shell to create the internal cavity where the clip would sit. This allowed the component to slide into the shell while maintaining the overall shape and structure of the housing.

<img width="1571" height="931" alt="Screenshot 2026-09-22 162934" src="https://github.com/user-attachments/assets/09176ac2-11fa-43cd-9b35-7d9bb37d74b3" />

**Figure 8:** Clip Bracket

I then created the bracket where the clips would rest and snap into place. A simple semicircular cutout was used to create the mating feature for the clip and provide a defined location for the snap-fit connection.

<img width="1491" height="797" alt="Screenshot 2026-09-22 163010" src="https://github.com/user-attachments/assets/2d207a4a-0b22-4472-b785-87dc3af9859d" />

**Figure 9:** Final Assembly

Finally, I assembled the two components using the Assembly feature in SolidWorks. The completed model shows that the clip and shell properly align and fit together, creating the intended snap-fit mechanism. The assembly also allowed me to verify the interaction between the two components before moving on to the 3D printing and testing stages.

<img width="507" height="727" alt="Screenshot 2026-09-22 004705" src="https://github.com/user-attachments/assets/0b4a4800-b9da-4ef0-a399-8a6da275c4fb" />




## 6. Design Decisions and Engineered Allowances

The snap-fit geometry was designed to allow the flexure to deflect during assembly and return toward its original position after passing the mating feature. The mating features were positioned to allow the two components to engage while preventing the parts from easily separating under the applied axial load.

The primary flexure dimensions were kept at the calculated values of **0.10 in × 0.20 in × 2.32 in** throughout the design process.

## 7. Overall CAD Design

The final SolidWorks model consists of two components that interact to form the completed snap-fit assembly. The use of parametric dimensions and geometric constraints allows the design to be modified efficiently if changes are needed during physical testing.

**Figure 6:** Overall snap-fit assembly in SolidWorks


# 3D Printing and Testing

