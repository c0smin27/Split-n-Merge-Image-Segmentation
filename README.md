# Split and Merge Image Segmentation with Python

## Description

This project implements an image segmentation technique using the **Split and Merge algorithm**, written in Python. It divides the image recursively into homogeneous regions, then merges adjacent ones based on intensity similarity. The project includes full visualization and step-by-step execution through an interactive notebook.

## How the Algorithm Works

1. **Split**: The image is recursively divided into quadrants until a homogeneity criterion is met.
2. **Merge**: Adjacent regions with similar pixel values are merged to reduce over-segmentation.
3. **Display**: The result is shown alongside the original image and intermediate segmentation states.

## Technologies Used

- Python (with Jupyter Notebook / nbconvert)
- Numpy
- OpenCV
- Matplotlib
- HTML export for presentation

## Disclaimer

This project was created as part of an academic assignment. Feel free to use it for learning purposes, but please do not submit it as your own work in educational settings.
