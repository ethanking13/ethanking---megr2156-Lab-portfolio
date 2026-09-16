
## Parameter — Tolerance Gauge Test

The parameter I chose to characterize on the Prusa Core One was **dimensional tolerance**. I chose to perform a tolerance gauge test to determine how small of a hole the printer could successfully produce.

I designed my own tolerance gauge using **Creo Parametric**. The artifact consisted of a small square with a series of progressively smaller holes. The hole diameters were **1.0 mm, 0.6 mm, 0.5 mm, 0.4 mm, 0.3 mm, 0.2 mm, 0.1 mm, and 0.09 mm**.

The purpose of using progressively smaller holes was to determine the minimum hole size that the Prusa Core One could successfully reproduce.

# Predicted Result

Before printing the artifact, I predicted that the **0.1 mm hole would not successfully print**. Since the printer was using a **0.4 mm nozzle**, I expected the smaller holes to become increasingly difficult to reproduce accurately. I expected the holes larger than 0.1 mm to be printable, while the **0.1 mm and 0.09 mm holes** would not successfully form.

## Document Process

I first created a flat square in Creo Parametric by sketching a square and extruding it to create the base of the artifact. I then created the circular cutouts and made each hole progressively smaller to create the tolerance gauge.

<img width="795" height="692" alt="Screenshot 2026-09-15 220350" src="https://github.com/user-attachments/assets/73d19a67-ce97-42fa-9139-3ca09d2d14ef" />

*Figure 1. Initial flat square extrusion.*

<img width="816" height="702" alt="Screenshot 2026-09-15 220356" src="https://github.com/user-attachments/assets/745f1b92-9ce8-49d3-b0ff-b4c03e2f2994" />

*Figure 2. Circular cutouts added to the artifact.*

<img width="851" height="717" alt="Screenshot 2026-09-15 203951" src="https://github.com/user-attachments/assets/4d818d90-d415-4b50-a584-7593de1de749" />

*Figure 3. Completed tolerance gauge in Creo Parametric.*

# Setting Up the Print

I placed the artifact flat on the build plate and used PLA with a 0.4 mm nozzle and 15% infill. I did not use supports because they were not necessary for the design. These settings were chosen to keep the test focused on the printer's ability to reproduce small holes.

<img width="777" height="557" alt="Screenshot 2026-09-15 222636" src="https://github.com/user-attachments/assets/caa41153-4a27-41f9-810f-bba6828e4663" />

*Figure 4. Final PrusaSlicer setup.*

# Slicing

After setting the print parameters, I sliced the model in PrusaSlicer and prepared it for printing on the Prusa Core One.

<img width="517" height="418" alt="Screenshot 2026-09-10 124012" src="https://github.com/user-attachments/assets/a3df8df9-effd-4c87-b7a4-ed368cdc9d08" />

*Figure 5. Sliced Model.*


<img width="478" height="677" alt="Screenshot 2026-09-10 122920" src="https://github.com/user-attachments/assets/71b9e73b-ee4e-43f2-938c-8133ad149fe4" />


*Figure 6. Printer Settings.*


<img width="495" height="535" alt="Screenshot 2026-09-10 124002" src="https://github.com/user-attachments/assets/cf2d1adc-ab2d-48aa-b11e-39432a2d86bd" />


*Figure 7. Printer Settings.*


<img width="422" height="402" alt="Screenshot 2026-09-10 124005" src="https://github.com/user-attachments/assets/4ba5f267-b49c-4c71-95dc-13d3362c8de0" />



*Figure 8. Printer Settings.*

# Printing

The artifact was then printed on the Prusa Core One using the selected settings.

<a href="../../images/IMG_6557.mp4" target="_blank">HERE</a>



*Figure 9. Video of the tolerance gauge being printed on the Prusa Core One.*

# Final Artifact

After the print was completed, I examined the holes to determine which sizes were successfully produced.

<img width="3024" height="4032" alt="IMG_6576" src="https://github.com/user-attachments/assets/a08c38d9-efc3-4a90-8ac4-b36a4f27c6ed" />


*Figure 10. Final printed tolerance gauge.*

## Preprocessor

# Infill

I used **15% infill** with the default infill pattern. Since the test focused on hole size and dimensional tolerance rather than strength, a higher infill percentage was not necessary.

# Build Orientation

The artifact was placed **flat on the build plate**. This kept the holes oriented consistently and avoided unnecessary overhangs.

# Supports

**No supports were used.** The artifact was flat on the build plate and did not require support material. This also prevented support material from interfering with the holes.

# Scale

The model was **scaled down in PrusaSlicer** because the original model from Creo Parametric was too large for the intended test. Scaling it down made the artifact a more practical size.

### PrusaSlicer Settings

- **Printer:** Prusa CORE One
- **Print Settings:** 0.25 mm Draft
- **Layer Height:** 0.25 mm
- **Material:** Generic PLA
- **Nozzle:** 0.4 mm
- **Infill:** 15%
- **Supports:** None
- **Orientation:** Flat on build plate
- **Scale:** Reduced

## Lessons Learned

# Comparison to Prediction

The result was the same as my original prediction. I predicted that the **0.1 mm and 0.09 mm holes would not successfully print**, and the final artifact showed that the **0.2 mm hole was the smallest hole that printed successfully**.

# Comparison to FDM Design Rules

The FDM design rules chart lists a tolerance of **±0.3%**, with a lower limit of **±0.3 mm**. My test showed that the **0.2 mm hole was the smallest feature that successfully printed**, while the smaller holes failed. Because the failed holes could not be accurately measured, I was unable to calculate the printer's exact tolerance from those features.

# Lessons Learned

1. **Nozzle size limits small features.** I learned that a 3D printer cannot always accurately produce every dimension designed in CAD. The **0.4 mm nozzle** made it difficult for the printer to produce the smaller holes, even though those dimensions were possible to create in Creo Parametric.

2. **Scale affects the practicality of the test.** The original model was too large, so I had to scale it down in PrusaSlicer. In the future, I would create the artifact closer to its final intended size in Creo Parametric.

3. **Print orientation can affect dimensional accuracy.** I kept the artifact flat on the build plate because the test focused on hole size. In future tests, I would consider how the orientation of a feature could affect its printed dimensions.

4. **Print settings affect feature resolution.** I used a **0.25 mm layer height and 15% infill**. In a future tolerance test, I could experiment with a smaller layer height to see if it improves the reproduction of small features.

5. **Measuring very small features can be difficult.** Because the smaller holes failed to print correctly, I was unable to accurately measure their actual diameter. This showed me that there is a practical limit to both the printer's ability to produce small features and my ability to measure them accurately.

# Total Project Time

The total time from designing the artifact to completing the print and evaluating the results was approximately **4 hours**.
