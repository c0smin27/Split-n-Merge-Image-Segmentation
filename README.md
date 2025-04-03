# Split and Merge Image Segmentation with Python

## Description

This project implements an image segmentation technique using the **Split and Merge algorithm**, written and executed in **Google Colab**. The image is recursively divided into homogeneous regions and then merged based on intensity similarity. The notebook includes full visualization, explanation, and step-by-step execution.

**❗❗ To properly view the complete project (including code, output, and visualizations), please download the `Split_and_Merge_Segmentation.html` file and open it locally in any web browser. ❗❗**

## How the Algorithm Works

1. **Split**: The image is recursively divided into quadrants until a homogeneity criterion is met.
2. **Merge**: Adjacent regions with similar pixel values are merged to reduce over-segmentation.
3. **Display**: The result is shown alongside the original image and intermediate segmentation steps.

## Technologies Used

- Python (**Google Colab**)
- Numpy
- OpenCV
- Matplotlib
- Jupyter Notebook (exported as HTML for presentation)

## Disclaimer

This project was created as part of an academic assignment. Feel free to use it for learning purposes, but please do not submit it as your own work in educational settings.
