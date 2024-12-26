# Introduction to Image Processing: Practical Notebooks

This repository contains practical notebooks for the course "Introduction to Image Processing." Each lab focuses on key concepts and techniques in image processing, combining theoretical insights with hands-on implementation. Below is a detailed summary of the content and skills applied in each lab.

## Lab 1: Radiometry and Contrast
- **Objective**: Understand the basic properties of images, their intensity distributions, and explore techniques to enhance image contrast.
- **Key Topics**:
  - **Histogram Analysis**: Calculation and visualization of simple and cumulative histograms.
  - **Histogram Equalization**: Redistribute intensity values to enhance image contrast.
  - **Histogram Prescription**: Match an image's histogram to a target histogram.
  - **Quantization**: Reduce intensity levels in an image for analysis.
  - **Dithering**: Simulate higher intensity levels through noise addition.
- **Skills Applied**:
  - Use of Python to manipulate and analyze image histograms.
  - Implementation of contrast enhancement and dithering techniques.
  - Practical understanding of histogram operations for image processing.

## Lab 2: Filtering and Wiener Restoration
- **Objective**: Explore filtering techniques and tackle image restoration using Wiener filtering.
- **Key Topics**:
  - **Geometric Transformations**: Rotation and scaling using nearest-neighbor and bilinear interpolation.
  - **Noise Reduction**: Comparison of linear (e.g., averaging) and nonlinear (e.g., median) filtering techniques.
  - **Equivalent Filters**: Design filters with equivalent performance across techniques.
  - **Inverse Filtering**: Address noise impact during restoration.
  - **Wiener Restoration**: Utilize spectral density and noise variance to restore degraded images effectively.
- **Skills Applied**:
  - Application of geometric transformations and interpolation methods.
  - Implementation and evaluation of denoising filters.
  - Deep understanding of Wiener filtering and its practical applications in restoration.

## Lab 3: Segmentation
- **Objective**: Apply diverse segmentation techniques to extract meaningful regions or objects from images.
- **Key Topics**:
  - **Edge Detection**:
    - Sobel filter to compute image gradients.
    - Local maxima detection in the gradient direction for refined edge detection.
    - Laplacian operator to identify zero-crossings.
  - **Clustering**:
    - K-Means for pixel classification in grayscale and color images.
  - **Thresholding**: Implement global and Otsu’s method for automatic threshold determination.
  - **Region Growing**: Segment regions iteratively based on intensity similarity.
- **Skills Applied**:
  - Advanced edge detection techniques.
  - Implementation of clustering algorithms for segmentation.
  - Application of region-based methods and thresholding for segmentation.

## Lab 4: Morphological Operations
- **Objective**: Understand and implement advanced morphological transformations for image preprocessing and segmentation.
- **Key Topics**:
  - **Binary Morphology**: Operations including erosion, dilation, opening, and closing.
  - **Grayscale Morphology**: Extension of binary operations to grayscale images.
  - **Alternating Filters**: Sequential applications of opening and closing for low-pass filtering effects.
  - **Watershed Segmentation**:
    - Application of morphological gradients.
    - Preprocessing using opening and closing for noise reduction and edge enhancement.
    - Marker-based watershed segmentation for precise results.
  - **Reconstruction Techniques**: Use morphological reconstruction for better segmentation markers.
- **Skills Applied**:
  - Practical use of morphological tools from `skimage.morphology`.
  - Design of advanced filtering and segmentation pipelines.
  - Application of marker-based methods to improve segmentation results.
