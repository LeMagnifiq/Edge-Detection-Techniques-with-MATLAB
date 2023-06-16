# Edge Detection Techniques: A Visualisation Analytics Project

## Introduction

This project focuses on the application and comparison of four edge detection approaches to identify edges in an image. Edge detection, a critical technique in image processing, computer vision, and machine vision, identifies object boundaries within images by detecting brightness discontinuities.

## Graphical User Interface (GUI)

The project's GUI includes two axes and five buttons. The first axis shows the original image, while the second displays the effects of the applied edge detection technique. The first button is for image selection, and the subsequent buttons activate each of the edge detection methods.

## Image 

The selected image for this project is a digitized JPG file featuring four bananas on a hexagonal grid with varying color gradients. The edge detection techniques applied include:

1. Canny Edge Detection
2. Sobel Edge Detection
3. Robert Edge Detection
4. Prewitt Edge Detection

### Canny Edge Detection

The Canny method uses two threshold levels to classify edges as weak and strong. It successfully detected most edges in the image and outlined the bananas clearly.

### Sobel Edge Detection

The Sobel Edge Detector approximates an image's vertical and horizontal attributes using two convolved 3 x 3 masks. However, it made the content of the image difficult to discern.

### Roberts Edge Detector

The Roberts Edge detector carries out a simple 2-D spatial gradient measurement on an image, making it easy to process. Yet, it detected fewer edges than the Canny and Sobel methods.

### Prewitt Edge Detection

The Prewitt edge detector, a gradient-based method, computes an approximation of an image’s intensity function’s angles through 3 x 3 masks. It revealed most edges in the image, albeit with significantly lower intensity.

## Conclusion

Among the four methods, the Canny Edge Detection technique outperformed the others. Although the Sobel, Prewitt, and Roberts edge detection methods presented challenges, the project highlights the efficacy of the Canny method. Further work is encouraged to refine existing techniques and devise more advanced and streamlined edge detection methods.

## How to Use

1. Clone or download this repository to your local machine.
2. Run the edge detection application.
3. Use the GUI to select an image and apply each edge detection technique to compare the results.
4. Experiment with different images to see the performance of the techniques on various edge detection scenarios.
