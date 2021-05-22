# HPC-Project
Comparison between GPU and CPU performance for image processing

This project will implement and compare various image processing algorithms running on both CPU 
and GPU. It presents an alternative approach to point-to-point processing of digital images by making 
use of multiple threads in grayscale, brightening, darkening, thresholding (RGB to Grayscale) and 
contrast adjustment algorithms. This technique is responsible for transforming each pixel on an image 
concurrently and not sequentially. The approach makes use of CUDA as a GPU platform to take 
advantage of all the available cores. In this project, computing performance of some common Image 
Processing operations are going to be implemented on python's inbuilt library OpenCV and compared 
to GPU functions that use CUDA.
