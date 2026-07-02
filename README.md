# Fall Detection using Kinect Depth Data

This repository contains a proof-of-concept for a Fall Detection system designed for Ambient Assisted Living (AAL) environments. 

The project explores the feasibility of a monitoring pipeline that relies **exclusively on depth data (depth maps)** acquired through a Microsoft Kinect v1 sensor.

## Dataset

This project utilizes the **UR Fall Detection Dataset**. [Link to the Dataset](https://fenix.ur.edu.pl/mkepski/ds/uf.html)

> Bogdan Kwolek, Michal Kepski, *Human fall detection on embedded platform using depth maps and wireless accelerometer*, Computer Methods and Programs in Biomedicine, Volume 117, Issue 3, December 2014, Pages 489-501, ISSN 0169-2607.  
> [Link](https://home.agh.edu.pl/~bkw/research/pdf/2014/KwolekKepski_CMBP2014.pdf)

## Project Structure

The entire analysis, pipeline development, and model training are contained and documented within a single Jupyter Notebook, divided into three main sections:

1. **Sensor Physics & Noise Modeling:** Introduction to the sensor, mathematical model for the kinect and its noise.
2. **Computer Vision Pipeline:** Filtering, depth-based background subtraction, feature extraction.
3. **Machine Learning & Evaluation:** Training and testing of a Random Forest model.

## Notebook

All source code, theoretical explanations, and critical conclusions are available here:

**[Fall Detection Using Kinect Depth Data](fall_detection.ipynb)**

## Video Demo

A complete visual demonstration of the processed dataset is available on YouTube. The video showcases the active Computer Vision pipeline, including depth masks, bounding boxes, floor plane estimations, and a real-time dashboard plotting the extracted spatial and kinematic features.

**[Pipeline Demo](https://youtu.be/Ls5-7-q5OKc)**

---
*Project developed for the Computer Vision and Image Processing course - University of Bologna.* *Author: Alfredo Grande*
