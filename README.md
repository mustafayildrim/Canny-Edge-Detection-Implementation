# Canny Edge Detection Implementation

## Description

This project implements the **Canny edge detection algorithm**, up to but not including the hysteresis step. The function, `MyCanny`, processes a **grayscale image** using edge detection parameters and returns a **binary edge map**. The implementation includes **Gaussian smoothing** and **gradient magnitude thresholding** to detect edges accurately without thickening.

## Features

- **Custom Canny Edge Detection (`MyCanny`)**
- **Gaussian Smoothing** using a standard deviation parameter (σ)
- **Gradient Magnitude Thresholding** with a threshold (τ)
- **Edge Map Output** for visualization
- **Parameter Tuning** for optimal edge detection results

## Technologies Used

- **Python**
- **NumPy**
- **Matplotlib**
- **Torch**
- **Kornia**

## Installation

```bash
pip install numpy matplotlib torch kornia
```

## Project Tasks

### **Task 1: Implement Gaussian Smoothing**
- Apply a **Gaussian filter** with standard deviation **σ** to remove noise.

### **Task 2: Compute Image Gradient**
- Use **Sobel filters** to compute gradient magnitude and direction.

### **Task 3: Apply Gradient Magnitude Thresholding**
- Filter out weak gradients based on **threshold τ**.

### **Task 4: Run Edge Detector on Test Images**
- Apply `MyCanny` on provided test images.
- Experiment with different **σ and τ values** to optimize results.

## Visualizations

- **Original vs. Edge-detected Image:** Compare input and processed edge maps.
- **Gradient Magnitude Map:** Visualize computed gradients before thresholding.
- **Effect of σ and τ:** Display variations in edge detection based on parameter changes.

## Acknowledgments

- **Pedro Felzenszwalb's** Canny edge detection handout.

