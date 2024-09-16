# Face-Mask-Detection
The system is built to help monitor and enforce face mask compliance in public places by providing real-time detection from images or video feeds. This project aims to provide accurate face mask detection and classification using a trained model with three key mask classes: with_mask, without_mask, and mask_weared_incorrect. Real-Time Detection: The system can be deployed on live video streams for real-time monitoring.
This project implements a Face Mask Detection system using a trained YOLOv8 model. It classifies faces in images or video streams into three categories:

With Mask: Faces wearing a mask correctly.
Without Mask: Faces not wearing a mask.
Incorrectly Worn Mask: Faces wearing a mask incorrectly.
Key Features
Multi-Class Detection: Detects three mask categories using YOLOv8.
MAPE Calculation: Evaluates model performance with Mean Absolute Percentage Error (MAPE).
Real-Time Detection: Can be used for live video feeds.

2. Install Dependencies
Once your virtual environment is activated (or if you are using your default environment), run the following command to install all the dependencies:


pip install -r requirements.txt
