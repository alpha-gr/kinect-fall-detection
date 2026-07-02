# Fall Detection using Kinect Depth Data

This repository contains a proof-of-concept for a Fall Detection system designed for Ambient Assisted Living (AAL) environments. 

The project explores the feasibility of a monitoring pipeline that relies **exclusively on depth data (depth maps)** acquired through a Microsoft Kinect v1 sensor.

## Project Structure

The entire analysis, pipeline development, and model training are contained and documented within a single Jupyter Notebook, divided into three main sections:

1. **Sensor Physics & Noise Modeling:** Introduction to the sensor, mathematical model for the kinect and its noise.
2. **Computer Vision Pipeline:** Filtering, depth-based background subtraction, feature extraction.
3. **Machine Learning & Evaluation:** Training and testing of a Random Forest model.

## Notebook

All source code, theoretical explanations, and critical conclusions are available here:

**[Fall Detection Using Kinect Depth Data](fall_detection.ipynb)**

---
*Project developed for the Computer Vision and Image Processing course - University of Bologna.* *Author: Alfredo Grande*
