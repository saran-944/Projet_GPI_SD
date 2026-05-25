## Projet_GPI_SD
# Cryo-EM Particle Picking Pipeline

*This project is an automated particle picking pipeline for cryo-electron microscopy. It uses Normalized Cross-Correlation (NCC) for micrographs to identify and extract particles.* 

> Steps: 

1. Pre-processing: binning, normalization, padding, and denoising.
2. Efficient Template Matching: NCC with and masking for detection.
3. Post-processing: local maximum filtering to isolate particle and prevent redundant detections.
4. Visualization: Generates score maps (NCC Score Maps) and facilitates particle extraction.

> Installation:

The project requires Python 3 and the following libraries: "requierement.txt"

> Usage:
1. Load your micrograph 
2. Define your template 
3. Run the main script
