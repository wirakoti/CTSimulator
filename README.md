# Cone-Beam Tomography Simulation

This project is a simulation of cone-beam computed tomography, written in Python. It allows users to generate sinograms from images using the Radon transform, perform inverse reconstruction, and export results in both PNG and DICOM formats. Additionally, basic image post-processing is available, such as  contrast adjustment.

## Features

- Implementation of the cone-beam Radon transform
- Generation of sinograms with customizable parameters (angle step, number of detectors, detector span)
- Inverse reconstruction of images from sinograms
- Export of reconstructed images as:
  - **PNG** (standard image format)
  - **DICOM** (medical image format with patient metadata)
- Contrast adjustment using OpenCV
- Interactive widgets for user input (via Jupyter Notebook)

## Authors 
- Mateusz Czechowski
- Wiktoria Białasik
