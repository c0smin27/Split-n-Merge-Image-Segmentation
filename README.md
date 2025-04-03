# Split and Merge Image Segmentation

## Description

This project implements the **Split and Merge algorithm** for image segmentation. It is designed to segment an image based on pixel intensity homogeneity by recursively dividing the image into smaller regions (splitting), and then merging adjacent regions that are similar.

The final result is visualized along with intermediate steps and a comparison to the original image.

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
