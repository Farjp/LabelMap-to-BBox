# LabelMap-to-BoundingBox
This project converts label maps in medical imaging to bounding boxes, visualizes them on axial CT slices, and overlays segmentation masks for context. It helps analyze segmentation outputs and ensures efficient debugging in medical image processing workflows.

# LabelMap-to-BBox

## Overview
This repository provides a tool to convert medical image label maps into bounding boxes and visualize them over CT slices. It enables efficient analysis and debugging of segmentation results by highlighting the bounding box and segmentation mask on axial slices of the CT image.

## Features
- Extracts bounding box dimensions (in voxel and physical units) from a given label map.
- Overlays the bounding box on an axial slice of the corresponding CT image.
- Visualizes the segmentation mask on the same slice for better interpretability.

## Requirements
- Python 3.x
- Required Python packages:
  - `SimpleITK`
  - `NumPy`
  - `Matplotlib`

Install the dependencies using:
```bash
pip install SimpleITK numpy matplotlib






