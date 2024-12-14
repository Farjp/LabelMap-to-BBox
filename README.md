# LabelMap-to-BoundingBox
This project extracts bounding boxes from segmentation maps (masks) in medical imaging datasets. If your dataset includes segmentation maps but lacks bounding boxes, this repository provides a solution to extract bounding boxes from the segmentation masks. It helps visualize these bounding boxes on axial CT slices and overlays the segmentation masks for context, aiding in efficient analysis and debugging of segmentation outputs in medical image processing workflows.

# LabelMap-to-BBox

## Overview
This repository provides a tool to convert medical image label maps into bounding boxes and visualize them over CT slices. It enables efficient analysis and debugging of segmentation results by highlighting the bounding box and segmentation mask on axial slices of the CT image.

## Features
- Extracts bounding box dimensions (in voxel and physical units) from a given label map.
- Overlays the bounding box on an axial slice of the corresponding CT image.
- Visualizes the segmentation mask on the same slice for better interpretability.
![Image Alt Text](https://github.com/Farjp/LabelMap-to-BBox/blob/main/Bbox-on-CT.png)

![Image Alt Text](https://github.com/Farjp/LabelMap-to-BBox/blob/main/Bbox-on-seg.png)
## Requirements
- Python 3.x
- Required Python packages:
  - `SimpleITK`
  - `NumPy`
  - `Matplotlib`

Install the dependencies using:
```bash
pip install SimpleITK numpy matplotlib
