### ND2 pseudocolour imaging and quantitative analysis

This repository contains a **Python workflow for batch processing and quantifying ND2 confocal microscopy data**.
It was developed for imaging-driven biology projects where microscopy images are treated as **quantitative data**, not just visual outputs.

The pipeline combines reproducible preprocessing, pseudocolour rendering, and **object-level measurement using scikit-image**, producing both images and structured CSV tables for downstream analysis.

### What this pipeline does

* Batch import of ND2 files
* Channel-specific preprocessing
* Pseudocolour RGB image generation
* Pixel-level and object-level quantification

Outputs include presentation-ready images and analysis-ready feature tables.

### Tools

Implemented in Python using:

* nd2reader
* scikit-image
* numpy, pandas
* tifffile, Pillow


### Outputs

For each ND2 file:

* Pseudocolour RGB image (TIFF and JPG)
* Per-file quantitative summary (`quant_summary.csv`)
* Object-level feature table extracted from signal regions

Example output:(example_rgb.jpg)


### Notes

* Object measurements are derived from **signal masks**, not full cell segmentation
* Inter-channel correlation is an intensity-based proxy
* The workflow prioritises robustness and transferability


**Author**
Yixiao Zhou
PhD Candidate, The University of Western Australia

**Note:** Raw ND2 data are not included due to file size constraints.
