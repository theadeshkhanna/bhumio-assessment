# Bhumio Assignment - Image Processing with Tesseract.js

This repository contains a simple JavaScript application developed for the assignment provided by Bhumio. The goal of the assignment is to extract user input from images, focusing on check marks in checkboxes and text written on lines.

## Assignment Task

Develop a JavaScript code that utilizes the Tesseract OCR engine for image processing. The application should be able to read the provided images and extract selective text, outputting the result in key=>value pairs.

## Input Files

The input images for this assignment can be found [here](https://drive.google.com/file/d/1-cI-Gb25U8-SRR16GGYv0GyCdau5ct_S).

## Desired Output

The JavaScript code should be capable of taking an image file as input and providing the output in the format of key=>value pairs.

## Implementation Details

The application utilizes Tesseract.js as the OCR library for image processing. While the assignment has been completed, there is a limitation with Tesseract.js regarding its inability to read tick marks and handwritten input accurately. To address this issue, it is recommended to train Tesseract.js for handwriting recognition.

Details on training Tesseract.js for handwriting recognition can be found in [this Stack Overflow answer](https://stackoverflow.com/questions/39556443/using-tesseract-for-handwriting-recognition).

## Documentation

For more information about the application and its API, refer to the [API documentation](https://documenter.getpostman.com/view/32664279/2s9YysE2cy).

## Repository Link

[GitHub Repository](https://github.com/theadeshkhanna/bhumio-assessment)
