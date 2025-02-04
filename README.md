# Facial Feature Analysis And BMI Prediction: OpenCv and DLIB

This project utilizes computer vision, dlib and regression models to predict Body Mass Index (BMI) from front-facing photograph of a person.This innovative approach harnesses the power of computer vision and deep learning to analyze facial features and predict BMI, offering a non-invasive and user-friendly alternative to traditional methods of BMI calculation.

## Table of Contents
- [About The Project](#about-the-project)
- [Getting Started](#getting-started)

## About The Project

Body Mass Index (BMI) is a widely used metric for assessing body weight relative to height, providing insights into an individual's health status. However, traditional BMI calculations require accurate measurements of height and weight, which may not always be readily available or convenient to obtain. This project addresses the need for a quick and accessible method to estimate BMI using facial images, making it easier for individuals to monitor their health.

For training of the model we used the following dataset:
[Illinois DOC labeled faces dataset](https://academictorrents.com/details/4b9b7e449aa732842aea1a7d4e6413f4507aea99)

In order to create a machine learning project. First we identified the facial features which affects the BMI(Body mass Index) of a person.The facial features are:
1. Cheek-to-Jaw Width Ratio (CJWR)
2. Width to Upper Facial Height Ratio (WHR)
3. Perimeter to Area Ratio (PAR)
4. Eye Size (ES)
5. Lower Face to Face Height Ratio (FW/FH)
6. Mean Eyebrow Height (MEH)

## Getting Started

Provide instructions on how to set up the project locally. This should include:
1. **Prerequisites**:
   * Jupyter notebook
   * python 3.12.1
2. The main.ipynb is the amin code to code run cell by cell. All the necessary libraries and packages will be installed.
3. the main2.ipynb conatns the models for reduced datatset.
4. test.ipynb is for testing images on the BMI predictor whch are present in the test images folder. To test a new image add the image in the test_images folder then change the path in the test code.
5. face_recognition.ipynb file continas the code for creating a gender classification model.

