# Dice-Detection-Yolo

## Project Overview
This project focuses on detecting and recognizing dice values using an Intel RealSense D435i camera and the YOLO object detection framework. The system captures images of dice, classifies the visible face value, and serves as a foundation for future integration with a UR robot for automated inspection and handling tasks.

### Objectives
The objectives of this project are:

Detect dice using computer vision and Roboflow
Recognize dice face values (1-6)
Train a YOLO model using a custom dataset
Use Intel RealSense camera for image acquisition
Prepare for future robot integration

### Hardware
The following hardware was used:

Intel RealSense D435i Camera
#Computer running Windows
#Custom dice dataset
#UR Robot (future integration)

### Software
The following software tools were used:

Python
OpenCV
Roboflow
Ultralytics YOLOv8
Visual Studio Code

### Dataset Collection
Images were collected using the Intel RealSense D435i camera positioned above the workspace.

Dataset statistics:

Total Images: 518
Dice Classes:
dice_1
dice_2
dice_3
dice_4
dice_5
dice_6

Different orientations and positions of the dice were captured to improve model robustness.

### Data Annotation
All images were uploaded to Roboflow and manually annotated.

Each dice image was assigned one of six classes corresponding to the visible face value:
dice_1
dice_2
dice_3
dice_4
dice_5
dice_6
The annotated dataset was exported in YOLO format.

### Training Workflow
RealSense Camera
        ↓
Image Collection
        ↓
Annotation (Roboflow)
        ↓
Dataset Export
        ↓
YOLOv8 Training
        ↓
Model Testing
        ↓
Real-Time Detection

### Project Status
Completed:

 RealSense camera setup
 Image collection
 Image annotation
 Dataset export

In Progress:

 YOLO model training
 Model evaluation
 Real-time detection

Future Work:

 UR robot integration
 Dice sorting automation
 Real-time robotic decision making

