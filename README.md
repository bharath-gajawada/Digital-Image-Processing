# Digital Image Processing Concepts & Implementations

This repository contains implementations of fundamental digital image processing techniques across several key areas:

## Basic Image Processing
- Image quantization and bit-depth manipulation
- Color space operations (RGB channel separation and processing)
- Brightness and contrast adjustment
- Grayscale conversion with multiple approaches
- Basic green screen background replacement
- Video frame processing and transitions

## Histogram Processing
- Histogram equalization for grayscale images
- Channel-wise histogram equalization for color images
- Histogram analysis and visualization
- Linear piecewise transformations
- Intensity transformations and mapping

## Filtering & Convolution
- Custom 2D convolution implementation
- Linear filtering:
  - Mean (average) filtering with optimization
  - Gaussian filtering with variable σ
  - Bilateral filtering with spatial and range parameters
- Non-linear filtering:
  - Median filtering
  - Adaptive filtering techniques
- Edge detection filters:
  - Sobel operator
  - Prewitt operator
  - Roberts cross operator
  - Laplacian filter
- Image sharpening:
  - Unsharp masking
  - High-boost filtering

## Frequency Domain Processing
- DFT (Discrete Fourier Transform) implementation:
  - 1D DFT
  - 2D DFT
  - Optimization using FFT (Fast Fourier Transform)
- Frequency spectrum analysis:
  - Magnitude spectrum processing
  - Phase spectrum manipulation
  - Signal reconstruction
- Audio signal processing using DFT
- Frequency domain filtering applications

## Morphological Operations
- Basic morphological operations implementation
- Skeletonization algorithms
- Shape detection and analysis
- Object counting and measurement
- Morphological noise removal

## Feature Detection & Segmentation
- Thresholding techniques:
  - Binary thresholding
  - Adaptive thresholding
  - Otsu's method
- Hough Transform implementations:
  - Line detection
  - Circle detection
- Harris Corner Detection
- Edge detection and enhancement
- Feature point analysis

## Special Applications
- Medical image enhancement
- Signature verification
- Fingerprint processing
- Noise removal for various noise types
- Image restoration techniques
- Steganography using LSB (Least Significant Bit)

Each implementation focuses on building algorithms from scratch with minimal library dependencies, emphasizing both theoretical understanding and practical optimization through vectorization techniques. The code includes comprehensive testing across various image conditions, parameter analysis, and performance benchmarking.