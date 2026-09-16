# Prusa Core One Tolerance Gauge Benchmark

**Name:** Ethan King  
**Course:** [Course Name]  
**Date:** [Date]

## Analyze — Parameter Selection

### Parameter Tested: Tolerance

The parameter selected for this project was **dimensional tolerance**, specifically the ability of the Prusa Core One to produce small internal holes.

To test this parameter, I designed a small square artifact containing a series of progressively smaller holes. The hole diameters ranged from **1.0 mm to 0.09 mm**.

The holes used in the test were:

- 1.0 mm
- 0.6 mm
- 0.5 mm
- 0.4 mm
- 0.3 mm
- 0.2 mm
- 0.1 mm
- 0.09 mm

The purpose of using progressively smaller holes was to determine the smallest hole that the Prusa Core One could successfully reproduce.

**[INSERT IMAGE OF FINAL CAD MODEL]**

**Figure 1.** Final CAD model of the tolerance gauge.

## Artifact Design

### CAD Design

The benchmark artifact was designed using **Creo Parametric**. The artifact consisted of a small square with multiple circular holes placed through the part. Each hole was progressively smaller than the previous hole.

The design was intentionally simple so that the test would focus primarily on the printer's ability to reproduce small holes rather than testing other characteristics such as overhangs or structural strength.

**[INSERT IMAGE OF CAD DESIGN PROCESS]**

**Figure 2.** Development of the tolerance gauge in Creo Parametric.

### Hole Dimensions

The hole diameters were designed to decrease from 1.0 mm to 0.09 mm. This provided a range of increasingly difficult features for the printer to reproduce.

| Hole | Diameter |
|---|---:|
| 1 | 1.0 mm |
| 2 | 0.6 mm |
| 3 | 0.5 mm |
| 4 | 0.4 mm |
| 5 | 0.3 mm |
| 6 | 0.2 mm |
| 7 | 0.1 mm |
| 8 | 0.09 mm |

**[INSERT IMAGE SHOWING HOLE DIMENSIONS IN CREO]**

**Figure 3.** Hole dimensions used in the tolerance gauge.

## Preprocessor — Predicted Result

Before printing the artifact, I predicted that the Prusa Core One would not be able to successfully produce the **0.1 mm hole**.

The prediction was based on the small size of the feature compared with the printer's **0.4 mm nozzle diameter**. I expected the larger holes to print successfully and the smaller holes to become increasingly difficult for the printer to reproduce.

I expected the **0.09 mm hole** to also be unsuccessful because it was even smaller than the predicted 0.1 mm limit.

**Predicted smallest successful hole:** 0.2 mm

**Predicted unsuccessful holes:** 0.1 mm and 0.09 mm

## PrusaSlicer Build Parameters

### Print Settings

| Setting | Value |
|---|---|
| Printer | Prusa Core One |
| Material | PLA |
| Nozzle Diameter | 0.4 mm |
| Infill | 15% |
| Infill Pattern | Default |
| Build Orientation | Flat on build plate |
| Supports | None |
| Scale | Scaled down |
| Layer Height | [INSERT ACTUAL VALUE] |
| Estimated Print Time | [INSERT ACTUAL VALUE] |

**[INSERT IMAGE OF PRUSASLICER SETTINGS]**

**Figure 4.** PrusaSlicer settings used for the tolerance gauge.

## Build Parameter Decisions

### Infill

The artifact was printed using **15% infill**. The default infill pattern was not changed.

The 15% infill was selected because the purpose of the artifact was to test **dimensional tolerance and small-hole reproduction**, not the structural strength of the part. A moderate amount of infill provided internal structure without adding unnecessary material or print time.

The infill was not increased because additional infill was not necessary for the tolerance test.

### Build Orientation

The artifact was positioned **flat on the build plate**.

This orientation was selected because the purpose of the test was to evaluate **tolerance and small-hole reproduction**, rather than the overhang capabilities of the Prusa Core One.

Keeping the artifact flat also provided a simple and consistent orientation for the test. This reduced the number of variables involved and allowed the experiment to focus on the size of the holes.

**[INSERT IMAGE OF BUILD ORIENTATION IN PRUSASLICER]**

**Figure 5.** Tolerance gauge positioned flat on the build plate.

### Supports

**Supports were not used.**

The geometry of the tolerance gauge did not require supports because the artifact was printed flat on the build plate. Avoiding supports also prevented support material from interfering with the holes being tested.

This helped keep the test focused on the printer's ability to reproduce the intended hole sizes.

### Scale

The model was **scaled down** before printing because the original dimensions created in Creo Parametric were too large for the intended tolerance test.

Scaling the model down made the artifact smaller and more practical for the test while maintaining the progressively smaller holes required for the experiment.

**[INSERT IMAGE OF SCALE SETTING]**

**Figure 6.** Scale adjustment applied to the tolerance gauge in PrusaSlicer.

### Other Build Parameters

[Add any other important PrusaSlicer settings or parameters used during the print.]

## Slice Information

**[INSERT IMAGE OF PRUSASLICER SLICE PREVIEW]**

**Figure 7.** Sliced tolerance gauge in PrusaSlicer.

The important slicing information for the print was:

- **Printer:** Prusa Core One
- **Material:** PLA
- **Nozzle:** 0.4 mm
- **Infill:** 15%
- **Supports:** None
- **Build Orientation:** Flat on build plate
- **Scale:** Reduced from the original CAD size
- **Layer Height:** [INSERT VALUE]
- **Estimated Print Time:** [INSERT VALUE]
- **Filament Used:** [INSERT VALUE]
- **Number of Layers:** [INSERT VALUE]

## Design Process

### Initial Design

The initial concept was to create a simple tolerance gauge that could test the printer's ability to reproduce progressively smaller holes.

**[INSERT IMAGE]**

**Figure 8.** Initial tolerance gauge concept.

### CAD Development

The artifact was developed in Creo Parametric by creating a small square and adding circular holes with decreasing diameters.

**[INSERT IMAGE]**

**Figure 9.** CAD development of the tolerance gauge.

### Final CAD Model

The final model contained eight holes ranging from **1.0 mm to 0.09 mm**.

**[INSERT IMAGE]**

**Figure 10.** Final CAD model before slicing.

### Slicing

The completed model was imported into PrusaSlicer. The model was scaled down, positioned flat on the build plate, and prepared for printing using PLA, 15% infill, and a 0.4 mm nozzle.

**[INSERT IMAGE]**

**Figure 11.** Tolerance gauge prepared for printing in PrusaSlicer.

### Printing

The final artifact was printed on the Prusa Core One using the selected build parameters.

**[INSERT IMAGE]**

**Figure 12.** Tolerance gauge during the printing process.

## Mistakes and Design Changes

One change made during the process was scaling the model down. The original dimensions created in Creo Parametric were too large for the intended test, so the model was scaled down before printing.

**Problem:** The original CAD dimensions were too large.

**Solution:** The model was scaled down in PrusaSlicer.

**Reason:** Scaling the model down created a more practical-sized artifact while maintaining the progressively smaller holes needed for the tolerance test.

**Effect:** The smaller artifact allowed the intended tolerance test to be performed.

[Add any additional mistakes or changes that occurred during the project.]

## Print Artifact

### Final Printed Artifact

**[INSERT IMAGE OF FINAL PRINT]**

**Figure 13.** Final printed tolerance gauge.

The final artifact was a small square containing eight progressively smaller holes. The printed artifact was used to determine the smallest hole that the Prusa Core One could successfully reproduce.

## Print Video

**[EMBED PRINT VIDEO HERE]**

**Figure 14.** Video of the tolerance gauge being printed on the Prusa Core One.

## Results

### Hole Test Results

Each hole was inspected to determine whether the printer successfully reproduced the intended opening.

| Designed Hole Diameter | Successfully Printed |
|---:|:---:|
| 1.0 mm | Yes |
| 0.6 mm | Yes |
| 0.5 mm | Yes |
| 0.4 mm | Yes |
| 0.3 mm | Yes |
| 0.2 mm | Yes |
| 0.1 mm | No |
| 0.09 mm | No |

**[INSERT IMAGE OF FINAL HOLES]**

**Figure 15.** Close-up view of the progressively smaller holes in the printed artifact.

### Actual Result

The Prusa Core One successfully reproduced holes from **1.0 mm down to 0.2 mm**.

The **0.1 mm and 0.09 mm holes were not successfully produced**.

Therefore, the smallest successfully reproduced hole in this test was:

**0.2 mm**

The smallest unsuccessful hole was:

**0.1 mm**

## Predicted vs. Actual Result

| | Result |
|---|---:|
| Predicted Limit | 0.1 mm |
| Smallest Successful Hole | 0.2 mm |
| Smallest Unsuccessful Hole | 0.1 mm |

The actual result was consistent with the prediction. Before printing, I predicted that the 0.1 mm hole would not successfully print. After printing the artifact, the 0.1 mm hole was not successfully produced, while the 0.2 mm hole was successfully produced.

The results established a practical tested limit of approximately **0.2 mm for the smallest successful hole** in this particular test.

## Comparison to Class Design Rules

The class design rules chart will be used to compare the measured result from this experiment to the expected FDM specification.

| Measurement | Value |
|---|---:|
| Class FDM Design Rule | [INSERT VALUE] |
| Predicted Result | 0.1 mm |
| Actual Smallest Successful Hole | 0.2 mm |

**[INSERT IMAGE OF CLASS FDM DESIGN RULES CHART]**

**Figure 16.** Relevant FDM design rule from the class design rules chart.

[Explain whether the measured result matched, exceeded, or fell short of the class specification.]

[Explain possible reasons for any difference between the experiment and the class design rule.]

Possible factors include:

- 0.4 mm nozzle diameter
- Layer height
- PLA material
- Print orientation
- Model scaling
- Printer settings
- Hole geometry
- Measurement or inspection method

## Lessons Learned

### Small Features Have Practical Limits

The test demonstrated that FDM printing has practical limits when producing extremely small internal features. Although the Prusa Core One successfully reproduced the 0.2 mm hole, it was unable to reproduce the 0.1 mm and 0.09 mm holes.

### Nozzle Size Affects Feature Reproduction

The printer used a **0.4 mm nozzle**, which is an important consideration when designing small features. The test showed that the printer can reproduce features smaller than the nozzle diameter, but there is still a point where the geometry becomes too small to reproduce successfully.

### Orientation Should Match the Test

Printing the artifact flat on the build plate helped keep the test focused on tolerance instead of overhang performance. This showed the importance of selecting an orientation based on the specific parameter being tested.

### CAD Design Must Consider Manufacturing

The original CAD model was too large for the intended test, so it had to be scaled down before printing. This demonstrated that the dimensions and overall size of a CAD model should be considered based on the manufacturing process and the purpose of the test.

### Predictions Help Evaluate Results

The prediction made before printing provided a reference for evaluating the final result. The prediction that the 0.1 mm hole would not print successfully was supported by the actual results.

## What I Would Change

### Add More Sizes Near the Limit

If I repeated the experiment, I would add more hole sizes between 0.1 mm and 0.2 mm. This would provide more information about the exact point where the printer stops successfully reproducing the holes.

### Take Actual Measurements

I would use a more precise measurement method to measure the actual diameter of the printed holes rather than only recording whether the hole was open or closed. This would provide quantitative data that could be directly compared to the CAD dimensions.

### Print Multiple Samples

I would print the tolerance gauge multiple times to determine whether the results were consistent between prints.

### Test Different Print Settings

I would test different layer heights or other PrusaSlicer settings to determine whether the printer could reproduce smaller holes under different conditions.

## Project Time

The total time required to complete the project from start to finish was approximately **4 hours**.

| Activity | Time |
|---|---:|
| Planning | [ ] |
| CAD Design | [ ] |
| Design Changes | [ ] |
| PrusaSlicer Setup | [ ] |
| Printing | [ ] |
| Testing | [ ] |
| Documentation | [ ] |
| **Total Project Time** | **Approximately 4 hours** |

## Conclusion

The purpose of this project was to characterize the dimensional tolerance of the Prusa Core One by testing its ability to reproduce progressively smaller holes.

A custom tolerance gauge was designed in Creo Parametric and contained holes ranging from **1.0 mm to 0.09 mm**. The artifact was printed using PLA, a 0.4 mm nozzle, 15% infill, no supports, and a flat build orientation.

Before printing, I predicted that the **0.1 mm hole would not successfully print**. The actual results supported this prediction. The printer successfully reproduced holes down to **0.2 mm**, while the 0.1 mm and 0.09 mm holes were unsuccessful.

The experiment demonstrated the importance of considering nozzle diameter, feature size, print orientation, scaling, and other manufacturing parameters when designing parts for FDM printing. The results can also be compared to the class FDM design rules to determine how the tested performance compares with the documented specification.
