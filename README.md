# LGMVIP--DataScience-Task-3

# Image to Pencil Sketch

This project demonstrates how to convert an image into a pencil sketch using OpenCV, a popular computer vision library. This project takes an input image and applies various image processing techniques to generate a pencil sketch effect.

# Introduction

In this project, The "Image to Pencil Sketch using OpenCV" is a Python project that allows users to convert a regular image into a pencil sketch using the OpenCV library. This project leverages various image processing techniques to achieve the desired effect.

You can transform any digital image into a realistic pencil sketch, simulating the texture and shading found in traditional hand-drawn sketches. The conversion process involves analyzing the input image, detecting edges, and applying specific filters to achieve the pencil sketch effect.

# Project Structure

To convert an image to a pencil sketch using OpenCV, follow these steps:



1. Import all the dependencies which are required .


2. Read the input image using the OpenCV library.


3. Convert the image from the BGR to RGB.


4. Convert the image from the BGR color space to the grayscale color space. This step simplifies the image and prepares it for edge detection.

5. Apply a bitwise bitwise_not operation to invert the colors of the grayscale image as well. This step prepares the grayscale image to be combined with the edge-detected image.


6. Apply a Gaussian blur to the grayscale image to reduce noise and smooth out any irregularities.

7. Apply a bitwise bitwise_not operation to invert the colors of the blur image as well. This step prepares the blur image to be combined with the edge-detected image.

8. Then dividing grayscale image and invert blur image we can get the sketch of the image and to see perfectly like a sketch we then convert that sketch image to BGR format.

# Conclusion

This project showcases the application of machine learning techniques for getting a pencil sketch of an image by OpenCV. By following the instructions provided, you can reproduce the model, evaluate its performance, and use it to make new realistic image to sketch

Also Understanding the new concept of OpenCV library which give a sketches

Feel free to explore the code and modify it as per your requirements. 
