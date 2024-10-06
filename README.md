
# Face Mask Detection System

This project implements a real-time **Face Mask Detection** system using the **YOLOv8** model. It helps monitor and enforce face mask compliance in public places by detecting and classifying face mask usage in images or video feeds.

## Key Features

- **Multi-Class Detection**: The system classifies faces into three categories:
  1. **With Mask**: Faces wearing a mask correctly.
  2. **Without Mask**: Faces not wearing a mask.
  3. **Incorrectly Worn Mask**: Faces wearing a mask incorrectly.
  
- **Real-Time Detection**: Capable of processing live video streams for real-time monitoring.
  
- **MAPE Calculation**: The system evaluates model performance using **Mean Absolute Percentage Error (MAPE)**.

## How It Works

1. **Model**: A pre-trained YOLOv8 model is used to detect faces and classify them into the three categories mentioned above.
2. **Data**: The system is trained on a dataset containing images of people with various mask-wearing statuses.
3. **Real-Time Application**: The trained model can be deployed on live video streams to provide instant feedback about mask compliance.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Face-Mask-Detection.git
   cd Face-Mask-Detection
2. Install dependencies:

   ```bash
    pip install -r requirements.txt

3. Download pre-trained weights: The model requires pre-trained weights for YOLOv8. You can download them and place them in the appropriate folder.
Example weight file: weights_resnet.pth


