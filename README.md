# Image-Processing-Experimentation
# Pipeline

Department of Computer Science and Engineering

## Overview

This project implements a complete image processing pipeline demonstrating the key stages of digital image analysis. The workflow includes image acquisition, preprocessing, noise simulation, filtering, segmentation, and feature extraction. The objective is to show how sequential image processing steps enhance image quality and extract meaningful information suitable for further computer vision applications.

## Features

* Image acquisition
* Grayscale conversion, resizing, and histogram equalization
* Gaussian and salt-and-pepper noise simulation
* Noise filtering using Gaussian and median filters
* Quantitative evaluation using PSNR and SSIM
* Object segmentation using Otsu thresholding, Canny edge detection, morphological operations, and watershed segmentation
* Feature extraction including contour detection, area, and centroid calculation
* Visualization of intermediate and final results

## Requirements

* Python 3.x
* OpenCV
* NumPy
* Matplotlib
* Scikit-Image

Install dependencies needed as mentioned above

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Sowmya-Anand/Image-Processing-Experimentation.git
   ```
2. Run the program:

   ```bash
   python main.py
   ```
3. Results from each stage will be displayed, including preprocessed, filtered, and segmented images with extracted features.

## Evaluation Metrics

* **PSNR (Peak Signal-to-Noise Ratio):** Measures restoration quality
* **SSIM (Structural Similarity Index):** Evaluates perceptual similarity

## License

This project is released under the MIT License.
