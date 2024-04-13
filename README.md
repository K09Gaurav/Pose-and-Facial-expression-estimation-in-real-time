# Real-time Pose Estimation and Facial Expression Recognition System

This Group project presents a real-time system that combines the capabilities of MediaPipe libraries and OpenCV to perform pose estimation and facial expression recognition simultaneously.

## Features

- **Self Database Creation**: Train your Dataset according to your needs and preferences. 
- **Real-time Pose Estimation**: Utilizes MediaPipe's advanced pose estimation model to accurately track key points of a person's body in real-time video streams.
- **Facial Expression Recognition**: Integrates MediaPipe's Face Mesh model with machine learning classifiers to recognize and classify various facial expressions in real-time.
- **Applications**: Enables fitness tracking, gesture-based interfaces, human activity monitoring, affective computing, and emotion-aware interfaces.
- **Integration**: MediaPipe and OpenCV integration provides a robust platform for understanding both human gestures and expressions.

## Technologies Used

- MediaPipe
- OpenCV
- Machine Learning Classifiers

## Usage

To use this system, follow these steps:

1. Clone the repository.
2. Install dependencies (specified in requirements.txt).
3. Run the file `Capturing_Data.ipynb`
4. You can customize the data to be recorded according to your reuirements.
5. Train the model in `Model.ipynb` using csv file generated.
6. You can select which machine learning algorith to use and export the model.
7. Run `RealTime_Detection.ipynb` on the model for the implementation