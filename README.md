## Projet_GPI_SD
# Cryo-EM Particle Picking Pipeline

*This project implements an automated particle picking pipeline for cryo-electron microscopy. The tool utilizes Normalized Cross-Correlation (NCC) optimized for micrographs to identify and extract protein particles..* 

> Steps: 

1. Advanced Pre-processing: Includes binning, normalization, padding, and denoising to enhance the signal-to-noise ratio.
2. Efficient Template Matching: Utilizes NCC with and masking for detection.
3. Post-processing: Implements local maximum filtering to isolate particle and prevent redundant detections.
4. Visualization: Generates score maps (NCC Score Maps) and facilitates particle extraction.

> Installation:
The project requires Python 3 and the following libraries: "requierement.txt"

> Usage:
1. Load your micrograph (e.g., .mrc or standard image formats).
2. Define your template (e.g., proj_xy in the script).
3. Run the main script:

Contributor
[Saran DEMBELE]
