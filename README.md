# Image Vision & Analysis (IV&A) Exercises

This repository contains a collection of fundamental and advanced image processing techniques implemented using Python. The primary focus is on digital image restoration, enhancement, and edge detection using libraries such as OpenCV, NumPy, and Scipy.

## 🚀 Overview

The notebook `IV&A Exercises.ipynb` provides practical implementations and comparative analyses of various computer vision algorithms. It covers everything from basic bit-plane slicing to complex deconvolution methods.

## 🛠 Features & Implementations

### 1. Image Enhancement & Filtering
* **Smoothing Filters:** Implementation of low-pass filters to reduce noise.
* **Global Histogram Equalization:** Enhancing image contrast by distributing pixel intensities.
* **High Pass & High Boosting:** Sharpness enhancement techniques to highlight fine details.
* **Bit Plane Slicing:** Analyzing the contribution of individual bits to the overall image.
* **Flexible Zooming:** Custom algorithms for image scaling and interpolation.

### 2. Edge Detection (Gradient & Morphological)
A comparative study of different edge detection operators:
* **Sobel Operator:** Gradient-based detection emphasizing horizontal and vertical edges.
* **Prewitt Operator:** Similar to Sobel but with different kernel weights.
* **Canny Edge Detection:** A multi-stage algorithm for optimal edge detection.
* **Morphological Gradient:** Utilizing dilation and erosion to find boundaries.

### 3. Image Restoration & Deconvolution
Advanced techniques to recover images from blur and noise:
* **Wiener Deconvolution:** Linear filter for reconstructing images degraded by a point spread function (PSF) and additive noise.
* **Richardson-Lucy Deconvolution:** Iterative procedure for restoring blurred images.
* **Point Spread Function (PSF) Generation:** Manual generation of Gaussian kernels for blurring simulations.

### 4. Custom Implementations
Includes manual "from-scratch" implementations (without direct OpenCV high-level functions) for:
* **2D Convolution**
* **Dilation and Erosion**
* **Morphological Gradient Calculation**

## 📦 Prerequisites

To run the exercises, ensure you have the following libraries installed:

```bash
pip install opencv-python numpy scipy matplotlib scikit-image
