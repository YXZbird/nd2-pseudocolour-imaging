# nd2-pseudocolour-imaging
Batch processing and pseudocolour rendering of ND2 confocal microscopy images using Python.
# ND2 Pseudocolour Imaging Pipeline

This repository provides a reproducible Python-based workflow for batch processing of ND2 confocal microscopy data, integrating image preprocessing, pseudocolour visualisation, and quantitative measurement using scikit-image.
The pipeline is designed for imaging-driven biological studies, where microscopy data are treated as quantitative measurements rather than purely visual outputs.

Overview

Confocal microscopy datasets often require:

channel-specific preprocessing
consistent visualisation across samples
extraction of quantitative features suitable for downstream analysis
This workflow addresses these needs by combining:
ND2 batch reading
robust preprocessing
pseudocolour rendering for visual inspection
pixel-level and object-level quantification

The emphasis is on transferable, modular analysis steps that can be adapted across biological systems.

**Note:** Raw ND2 data are not included due to file size constraints.
