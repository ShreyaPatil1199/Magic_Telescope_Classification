# Magic_Telescope_Classification

![image](https://github.com/ShreyaPatil1199/Magic_Telescope_Classification/assets/135635788/1fbfba9c-34d3-4f58-a923-3bd28dd5cb5a)

Welcome to the MAGIC Gamma Telescope project! 🌌 The mission is to classify gamma rays and hadrons in astrophysics using machine learning techniques like Logistic Regression, Decision Tree, Random Forest, and Ensemble. The primary objective is to develop a classification prediction system capable of distinguishing between gamma rays and hadrons in the field of astrophysics.

Classifying Gamma and Hadron rays is of paramount importance in unravelling the mysteries of the universe, and the valuable MAGIC Telescope dataset aids us in achieving this goal. To accomplish this task, various machine learning techniques are employed, including Logistic Regression, Decision Tree, Random Forest, and Ensemble Techniques, to predict and differentiate between these high-energy particles.

The ultimate aim is to create a reliable and accurate prediction model that effectively classifies Gamma and Hadron rays. 🚀 #Astrophysics #MachineLearning

![GitHub](https://img.shields.io/github/license/Shreyapatil1199/Magic_Telescope_Classification)

![GitHub release (latest by date)](https://img.shields.io/github/v/release/Shreyapatil1199/Magic_Telescope_Classification)

![GitHub last commit](https://img.shields.io/github/last-commit/Shreyapatil1199/Magic_Telescope_Classification)

## Overview
  This project aims to classify high-energy particles, specifically gamma rays and hadron rays, detected by the MAGIC Gamma Telescope. The dataset contains the following 
  features:
  
  **fLength**: Represents the major axis of an ellipse in millimetres. The major axis is the longest diameter of the elliptical shape formed by the detected particle. (Unit of 
  measurement: mm)
  
  **fWidth**: Indicates the minor axis of the ellipse in millimetres. The minor axis is the shortest diameter of the elliptical shape. (Unit of measurement: mm)
  
  **Size**: Represents the logarithm (base 10) of the sum of the content of all the pixels in the image. It provides information about the overall magnitude or intensity of 
  the detected signal. (Unit of measurement: mm)
  
  **fConc**: Measures the ratio of the sum of the two highest pixels' values over fSize. It provides insight into the concentration or distribution of pixel values within the 
  image. (Unit of measurement: dimensionless ratio)
  
  **fAsym**: Measures the distance from the highest pixel to the centre of the ellipse, projected onto the major axis in millimetres. It provides information about the 
  asymmetry or displacement of the signal with respect to the centre. (Unit of measurement: mm)
  
  **fConc1**: Represents the ratio of the value of the highest pixel over fSize. This variable provides information about the dominance or intensity of the highest pixel in 
  the image. (Unit of measurement: dimensionless ratio)
  
  **fM3Long**: Represents the third root of the third moment along the major axis of the ellipse in millimetres. The third moment is a statistical measure that provides 
  information about the shape or distribution of pixel values along the major axis. (Unit of measurement: mm)
  
  **fM3Trans**: Indicates the third root of the third moment along the minor axis of the ellipse. It provides information about the shape or distribution of pixel values along 
  the minor axis. (Unit of measurement: mm)
  
  **fAlpha**: Represents the angle (in degrees) between the major axis of the ellipse and a vector connecting the origin (coordinate [0, 0]) to the ellipse's centre. It 
  provides information about the orientation or alignment of the detected signal. (Unit of measurement: degrees [°])
  
  **fDist**: Represents the distance from the origin to the centre of the ellipse in millimetres. It provides information about the spatial position or radial distance of the 
  detected signal. (Unit of measurement: mm)
  
  **class**: This variable indicates the class or type of the detected signal. It has two categories: "g" for gamma rays (signal) and "h" for hadron rays (background). This 
  variable is used for classification purposes, distinguishing between gamma rays and hadron rays. (TARGET VARIABLE > Class)

## Citation

Citation: Bock,R.. (2007). MAGIC Gamma Telescope. UCI Machine Learning Repository. https://doi.org/10.24432/C52C8B.
