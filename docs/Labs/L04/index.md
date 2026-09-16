## Parameter — Tolerance Gauge Test

The parameter I chose to characterize on the Prusa Core One was **dimensional tolerance**. I chose to perform a tolerance gauge test to determine how small of a hole the printer could successfully produce.

I designed my own tolerance gauge using **Creo Parametric**. The artifact consisted of a small square with a series of progressively smaller holes. The hole diameters were **1.0 mm, 0.6 mm, 0.5 mm, 0.4 mm, 0.3 mm, 0.2 mm, 0.1 mm, and 0.09 mm**.

The purpose of using progressively smaller holes was to determine the minimum hole size that the Prusa Core One could successfully reproduce.

### Predicted Result

Before printing the artifact, I predicted that the **0.1 mm hole would not successfully print**. Since the printer was using a **0.4 mm nozzle**, I expected the smaller holes to become increasingly difficult to reproduce accurately. I expected the holes larger than 0.1 mm to be printable, while the **0.1 mm and 0.09 mm holes** would not successfully form.

**Predicted limit: 0.1 mm**

## Decide — Build Parameters

The build parameters were chosen to focus the test on **dimensional tolerance and small-hole reproduction**.

| Parameter | Setting |
|---|---|
| Material | PLA |
| Nozzle | 0.4 mm |
| Infill | 15% |
| Orientation | Flat on build plate |
| Supports | None |
| Scale | Scaled down |

# Infill
I used **15% infill** with the default pattern because the test focused on hole size rather than part strength.

# Orientation
The artifact was printed **flat on the build plate** because I was testing tolerance, not overhang performance.

# Supports
**No supports were used** because they were not needed for the flat geometry and could interfere with the holes.

# Scale
The model was **scaled down** because the original Creo dimensions were too large for the intended test.

## Document Process

I first created a flat square in Creo Parametric by sketching a square and extruding it to create the base of the artifact. I then created the circular cutouts and made each hole progressively smaller to create the tolerance gauge.

<img width="795" height="692" alt="Screenshot 2026-09-15 220350" src="https://github.com/user-attachments/assets/73d19a67-ce97-42fa-9139-3ca09d2d14ef" />

*Figure 1. Initial flat square extrusion.*

<img width="816" height="702" alt="Screenshot 2026-09-15 220356" src="https://github.com/user-attachments/assets/745f1b92-9ce8-49d3-b0ff-b4c03e2f2994" />

*Figure 2. Circular cutouts added to the artifact.*

<img width="851" height="717" alt="Screenshot 2026-09-15 203951" src="https://github.com/user-attachments/assets/4d818d90-d415-4b50-a584-7593de1de749" />

*Figure 3. Completed tolerance gauge in Creo Parametric.*

### Setting Up the Print

I placed the artifact flat on the build plate and used PLA with a 0.4 mm nozzle and 15% infill. I did not use supports because they were not necessary for the design. These settings were chosen to keep the test focused on the printer's ability to reproduce small holes.

<img width="517" height="418" alt="Screenshot 2026-09-10 124012" src="https://github.com/user-attachments/assets/fd5f5e95-576d-4d52-a887-aa0e370695cb" />

*Figure 4. Final PrusaSlicer setup.*

### Slicing

After setting the print parameters, I sliced the model in PrusaSlicer and prepared it for printing on the Prusa Core One.

<img width="517" height="418" alt="Screenshot 2026-09-10 124012" src="https://github.com/user-attachments/assets/a3df8df9-effd-4c87-b7a4-ed368cdc9d08" />

*Figure 5. Printer Settings.*


<img width="777" height="557" alt="Screenshot 2026-09-15 222636" src="https://github.com/user-attachments/assets/caa41153-4a27-41f9-810f-bba6828e4663" />


*Figure 6. Printer Settings.*


<img width="495" height="535" alt="Screenshot 2026-09-10 124002" src="https://github.com/user-attachments/assets/27e3deea-4088-4630-9e7f-d0e730f0c6b4" />


*Figure 7. Printer Settings.*


<img width="422" height="402" alt="Screenshot 2026-09-10 124005" src="https://github.com/user-attachments/assets/fbefaa89-d914-45d7-81d1-047b5ee83695" />


*Figure 8. Printer Settings.*


### Printing

The artifact was then printed on the Prusa Core One using the selected settings.

<a href="../../images/IMG_6557.mp4" target="_blank">HERE</a>



*Figure 10. Video of the tolerance gauge being printed on the Prusa Core One.*

### Final Artifact

After the print was completed, I examined the holes to determine which sizes were successfully produced.

<img width="3024" height="4032" alt="IMG_6576" src="https://github.com/user-attachments/assets/a08c38d9-efc3-4a90-8ac4-b36a4f27c6ed" />


*Figure 11. Final printed tolerance gauge.*
