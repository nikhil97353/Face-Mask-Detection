# Face-Mask-Detection
This project implements a Face Mask Detection system using a trained YOLOv8 model. It classifies faces in images or video streams into three categories:

With Mask: Faces wearing a mask correctly.
Without Mask: Faces not wearing a mask.
Incorrectly Worn Mask: Faces wearing a mask incorrectly.
Key Features
Multi-Class Detection: Detects three mask categories using YOLOv8.
MAPE Calculation: Evaluates model performance with Mean Absolute Percentage Error (MAPE).
Real-Time Detection: Can be used for live video feeds.


On Windows:

.\venv\Scripts\activate

2. Install Dependencies
Once your virtual environment is activated (or if you are using your default environment), run the following command to install all the dependencies:


pip install -r requirements.txt

3. Deactivating the Virtual Environment
After working on the project, you can deactivate the virtual environment using the command:
deactivate
