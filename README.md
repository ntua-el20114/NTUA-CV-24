# Computer Vision Laboratory (NTUA ECE)

This repository contains the laboratory assignments and implementations for the Computer Vision course at the National Technical University of Athens (NTUA), School of Electrical and Computer Engineering. The coursework is divided into two main modules, focusing on fundamental and advanced topics in computer vision, image processing, and video analysis. 

The implementation is primarily conducted in Python using Jupyter Notebooks, leveraging established scientific computing libraries such as OpenCV, NumPy, and SciPy.

## Repository Structure

### [Lab 1: Image Processing and Feature Extraction](./Lab1)
This module explores foundational techniques in low-level vision, specifically targeting edge detection, interest point localization, and local feature descriptors.

* **Part 1: Edge Detection in Grayscale Images** (`lab1_part1.ipynb`)
  Focuses on the implementation, evaluation, and mathematical analysis of edge detection algorithms on grayscale representations of natural images.
* **Part 2: Interest Point Detection** (`lab1_part2.ipynb`)
  Addresses the formulation and implementation of algorithms for robustly localizing key spatial interest points (e.g., corners) within images.
* **Part 3: Image Matching and Classification** (`lab1_part3.ipynb`)
  Investigates the application of local descriptors extracted from interest points for complex tasks such as image matching (robust to rotation and scale variations) and image categorization.

### [Lab 2: Motion Analysis, Video Processing, and Image Stitching](./Lab2)
This module transitions to spatiotemporal analysis and multi-view geometry, covering optical flow estimation, human action feature extraction, and panoramic image generation.

* **Part 1: Face and Hand Tracking Using Lucas-Kanade Optical Flow** (`part1.ipynb`)
  Involves the estimation of optical flow utilizing the Lucas-Kanade differential method to reliably track human faces and hands across sequential video frames.
* **Part 2: Spatiotemporal Interest Point Detection and Feature Extraction** (`part2.ipynb`)
  Extends spatial interest point detection into the temporal domain, enabling the extraction of invariant features from video sequences for human action analysis.
* **Part 3: Image Stitching for Panorama Creation** (`part3.ipynb`)
  Covers the complete pipeline for image stitching, including feature matching, robust homography matrix estimation (e.g., via RANSAC), and image warping to synthesize panoramic views from multiple overlapping photographs.

## Dependencies

The computational notebooks are designed to be executed within a standard scientific Python ecosystem. The primary dependencies include:
- `numpy`: Numerical computation and matrix operations.
- `opencv-python` (`cv2`): Core computer vision algorithms and image transformations.
- `scipy`: Advanced mathematical functions and signal processing.
- `matplotlib`: Data visualization and image display.
- `jupyter`: Interactive notebook execution environment.

## Execution Guidelines

To replicate the experiments and analyses, navigate to the respective laboratory directories and initialize the Jupyter Notebook server:

```bash
# Navigate to the desired laboratory directory
cd Lab1  # or cd Lab2

# Launch the Jupyter Notebook environment
jupyter notebook
```

Execute the notebook cells sequentially within each respective file to observe the algorithmic implementations, mathematical derivations, intermediate visualizations, and final empirical results.
