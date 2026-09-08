# A3 – [Design Something Small]

## Design
First I had to come up with a design that met the assignment requirements (1.5in x 1.5in x 0.5in Tall). And a print that would be less than 1.5 Hours.

I decided to go with an ash tray, It has zero reason behind it. I saw it as a simple design and a couple of CAD variations and that was it.

I first started with a circle then I extruded it to the required height.
<img width="1323" height="782" alt="Screenshot 2026-09-07 232008" src="https://github.com/user-attachments/assets/99c3e9e3-0dab-4e22-a12e-8081d22fe973" />

I then made cutouts of the "holder". 
<img width="1332" height="777" alt="Screenshot 2026-09-07 232027" src="https://github.com/user-attachments/assets/e7326cf4-8418-4f46-8ed0-7cf79f051a66" />

I then hollowed out the inside, and mirrored the cutout for the ash tray.
<img width="1318" height="782" alt="Screenshot 2026-09-07 232040" src="https://github.com/user-attachments/assets/4138e943-98a2-42ad-9c1a-c52a1826ae16" />


CAD Model Total Steps
<img width="352" height="382" alt="Screenshot 2026-09-03 120546" src="https://github.com/user-attachments/assets/0aeb11c7-eb58-4d20-8bf5-c36ca84d6659" />


## Research
# Gyroid Infill

Gyroid infill is a three-dimensional structure that provides relatively equal strength in all directions. It also has a good strength-to-weight ratio, prints fairly quickly, and uses material efficiently.

# Cubic Infill

Cubic infill uses paths that cross within each layer to create three-dimensional cubes with air pockets inside. These air pockets can provide insulation or help the object float when using waterproof materials such as PETG.

# Grid Infill

Grid infill is one of the simplest and fastest infill patterns, with lines printed in two directions to create a grid. It is more solid than rectilinear infill and provides better layer adhesion, but the accumulated material at the crossings can sometimes cause printing issues.

# Effect of Infill Percentage

Increasing the infill percentage generally makes a part stronger and more rigid because more material is used inside the part. However, higher infill also increases material usage and print time, while lower infill reduces material and print time but can decrease strength. While Different infill patterns distribute material and forces differently, which affects the strength, stiffness, and overall performance of a part. The best infill pattern depends on the direction and type of forces the part will experience, as well as the desired balance between strength, material usage, and print time.


## Preprocessor and Printing
When I first opened the model in PrusaSlicer, it was positioned vertically. I changed the orientation so that the bottom of the object was parallel with the build plate. I chose this orientation because the object needed to have a flat bottom surface. This allowed the object to sit properly on the build plate and gave it the correct orientation for printing.

I scaled the model in the X direction to 1.5×. This was done because the assignment allowed the model to be scaled to the required dimensions of 1.5 in × 1.5 in × 0.5 in. Scaling the X direction allowed me to meet the required dimensions while keeping the model within the specifications of the assignment.


The infill was left at the default PrusaSlicer setting. I did not make any changes to the default infill because the default setting was appropriate for the part and the assignment did not require a different infill. Keeping the default setting also avoided making unnecessary changes to the print.


The wall thickness was set to 0.5 in. I chose a thinner wall thickness because I wanted to use less material and reduce the overall print time. Different wall thicknesses can be used depending on the requirements of the part. Thicker walls generally provide more strength and durability, while thinner walls can reduce material usage and printing time when additional strength is not necessary.


I followed the instructions carefully throughout the process because I wanted to avoid making mistakes. The main issue I encountered was the initial orientation of the model. When I first imported the model into PrusaSlicer, it was positioned vertically instead of having the bottom parallel with the build plate. I noticed this before printing and corrected the orientation. Other than the orientation issue, I did not encounter any major mistakes because I carefully checked the settings and followed the assignment requirements throughout the process.

Final Model with correct orientation.
<img width="337" height="222" alt="Screenshot 2026-09-03 120421" src="https://github.com/user-attachments/assets/94c17951-c625-4804-9ec0-139df0707a53" />

## Print

Below is a photo of the Prusa Printer starting to heat up 
<img width="4284" height="5712" alt="IMG_6524" src="https://github.com/user-attachments/assets/ecdca149-8fed-4fea-b982-db81e56a7b9f" />

And in this video is a picture of the Prusa printing me and my groups assignments,

<video controls width="600">
    <source src="images/IMG_6525.mov" type="video/quicktime">
</video>



<a href="../../images/IMG_6525%20(1).mov" target="_blank">HERE</a>




# Completed Print
<img width="3024" height="4032" alt="IMG_6529" src="https://github.com/user-attachments/assets/bd6587cf-cbc0-459a-b8a5-84f6aa2865d2" />


# Model Information
<img width="481" height="660" alt="Screenshot 2026-09-03 120959" src="https://github.com/user-attachments/assets/3e2bf34e-f8e2-4ac8-ae22-d499c36a0111" />

# Slicer Information
<img width="427" height="297" alt="Screenshot 2026-09-03 121046" src="https://github.com/user-attachments/assets/68ff6daa-59ac-4794-8856-e7f6e38803d3" />


## Lessons Learned

# Lessons Learned

Throughout this project, I learned how infill and wall thickness affect the strength, material usage, and print time of a 3D-printed part. I learned that these settings should be chosen based on what the part will be used for. This helped me better understand how small changes in the slicer can affect the final product.

# Mistakes and Fixes

The main mistake I caught was the model being vertical when I imported it into PrusaSlicer, so I rotated it until the bottom was parallel with the plate. I also remembered a previous mistake where I accidentally moved the slicer layer and only printed the first layer. To prevent this in the future, I would check the entire layer preview and all slicer settings before printing.

# Time and Resources

The entire process took approximately two hours, from opening the assignment and creating the CAD model to preparing and printing the ashtray. I used Creo to create the model, PrusaSlicer to prepare the print, and a 3D printer to produce the final part. I also used internet pictures as a reference for the ashtray design.

# Scaling Up the Decision

If this were a structural or safety-critical part, I would use thicker walls and higher infill to provide more strength and stability. Using walls or infill that were too low could cause the part to bend, crack, or fail under a larger load. Unlike the ashtray, a safety-critical part would require much more testing and consideration of the forces it will experience.

# Real Product Connection

A similar decision is made when designing plastic automotive components such as cup holders or storage trays. Engineers must choose an appropriate wall thickness and material so the part is strong enough without unnecessarily increasing material usage, weight, or manufacturing time. This is similar to my ashtray because both require balancing strength, material, and production time.


## Resources
[PrusaSlicer Infill Patterns](https://help.prusa3d.com/article/infill-patterns_177130)
