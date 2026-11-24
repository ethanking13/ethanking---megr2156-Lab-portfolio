# A10 – RC2 Sliding Fit

## Research and Planning

The ASME RC 2 sliding fit allows two parts to slide smoothly together while maintaining a small clearance. It is commonly used in sliding shafts and mechanical guide systems.

**Nominal Diameter:** 1.000 inches

**Hole Dimensions:**
- Minimum: 1.0000 in
- Maximum: 1.0005 in

**Shaft Dimensions:**
- Minimum: 0.9993 in
- Maximum: 0.9997 in

**Clearance:**
- Minimum: 0.0003 in
- Maximum: 0.0012 in

**Hand Sketches:**

<img width="1209" height="998" alt="IMG_0466" src="https://github.com/user-attachments/assets/64b8454c-7536-4590-bd37-c38eb421f51a" />


**Real-World Applications:**

RC 2 sliding fits are used in mechanical systems where parts need to slide smoothly while maintaining accurate positioning. Examples include sliding shafts, guide mechanisms, and precision machinery.

**Resin Shrinkage and Compensation:**

The parts will be printed using a Formlabs Form 4 with Standard Resin. Resin can shrink slightly during curing, which can affect the final dimensions. To account for this, the initial CAD dimensions will be 1.00025 inches for the hole and 0.99950 inches for the shaft. The printed parts will be measured after curing and adjusted if necessary to achieve the desired RC 2 sliding fit.

## CAD Design
**Part A:**
<img width="1106" height="517" alt="Screenshot 2026-11-23 212422" src="https://github.com/user-attachments/assets/2a283d95-624d-4bb8-8c47-da21aa9824be" />
<img width="900" height="585" alt="Screenshot 2026-11-23 212433" src="https://github.com/user-attachments/assets/1a4c1e49-7d45-4f52-844f-e65fe88b114d" />
**Part B:**
<img width="1152" height="542" alt="Screenshot 2026-11-23 212550" src="https://github.com/user-attachments/assets/68b1323f-70f7-4ab7-bac0-5dc0ad968312" />
<img width="962" height="525" alt="Screenshot 2026-11-23 212556" src="https://github.com/user-attachments/assets/43a74826-e388-478d-b6a3-382662483392" />

I more so ended up estimating the shrinkage because I unfortunately wasn't able to get access to a printer until the day before. So my nominal and tolerances were up to the printer.

# 3D Printing Setup – PreForm

## Machine Information
- **Slicer Software:** PreForm
- **3D Printer:** MatureImpala
- **Material:** Grey V5

## Build Orientation
The part was positioned on the build plate so that the support structures would not contact or interfere with the sliding-fit surfaces. This orientation was selected to prevent support removal from damaging the mating surfaces or affecting their dimensional accuracy. Maintaining smooth and accurate sliding-fit surfaces is important to ensure that the two components fit together and move as intended after printing.

- **Build Orientation:** Positioned to keep supports away from the sliding-fit surfaces.
- **Reasoning:** Minimize support contact on critical mating surfaces to preserve surface finish, dimensional accuracy, and proper clearance between the two parts.

## Build Plate Layout
The build plate was arranged to accommodate multiple student parts while maintaining sufficient spacing between components.

<img width="793" height="490" alt="Screenshot 2026-11-23 214227" src="https://github.com/user-attachments/assets/421ca4ee-a0c6-43a9-a92b-8c03ac4a8cc0" />
<img width="405" height="162" alt="Screenshot 2026-11-23 214317" src="https://github.com/user-attachments/assets/6e542f46-4601-4917-9deb-36de29cbebf6" />

## Post-Processing
<img width="4284" height="5712" alt="IMG_6843" src="https://github.com/user-attachments/assets/abb9a50f-3dda-43f2-84e0-ca53b4478fca" />
<img width="4284" height="5712" alt="IMG_6844" src="https://github.com/user-attachments/assets/4e1e97e3-16b8-4fc3-99ca-94a1ea102cb4" />

The finishing on the model was very smooth, Other than the parts that were clipped off from the supports. The dimensional deviations didnt really occur it all fit together pretty well

## Fit Test
<img width="3024" height="4032" alt="IMG_6915" src="https://github.com/user-attachments/assets/69f6674a-727f-4f1c-b91c-3871a8560151" />
<img width="3024" height="4032" alt="IMG_6916" src="https://github.com/user-attachments/assets/0ff1d87b-90f3-470b-9d44-a02c25aa4d73" />
<img width="3024" height="4032" alt="IMG_6917" src="https://github.com/user-attachments/assets/70098444-0acd-4bf3-a6ea-93469a42f7c7" />

Overall the fitment was very tight but it did slide in an out roughly, Before I presented my model I accidently broke part of the end that slid onto the part.

## Reflection and Lessons Learned

## Challenges
The biggest challenge was finding the proper fit so that all the components worked together correctly. It took some trial and error to get the clearance right without making the fit too tight or too loose.

## Surface Finish
The surface finish was very high quality and did not cause any noticeable problems with the fit. The printed parts came out smooth and clean.

## Improvements for Next Time
Next time, I would reduce the dimensions by approximately 0.001 inches (1 thou) to achieve a better fit. I would make small adjustments carefully to avoid removing too much material or accidentally breaking the part.

## Time and Resources
- **Total Time Spent:** Approximately 5 hours
- **CAD Software:** Creo Parametric
- **Slicer Software:** PreForm
- **Reference:** Machinery's Handbook, 32nd Edition
- **Tools:** Digital caliper, micrometer, and 3D printer

## Overall Reflection
I learned how important small dimensional adjustments are when designing parts that need to fit together. Even a difference of one thousandth of an inch can affect how the components work together. Testing and making small adjustments helped me better understand manufacturing tolerances and sliding fits.
