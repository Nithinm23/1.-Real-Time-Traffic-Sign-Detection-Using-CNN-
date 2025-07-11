Real-Time Traffic Sign Detection Using CNN
Overview
<p align="justify"> Project RTS is an advanced real-time traffic sign detection and recognition system designed to enhance road safety and support intelligent transportation solutions. Leveraging deep learning and computer vision, the system identifies and classifies traffic signs from live video feeds, providing instant feedback crucial for driver assistance systems and autonomous vehicles. The model is trained on diverse datasets of Indian and German traffic signs to ensure robust performance across various conditions.
Abstract
<p align="justify"> Project RTS implements a real-time pipeline for detecting and classifying traffic signs using a custom Convolutional Neural Network (CNN) architecture. Trained on approximately 35,000 labeled images covering 43 classes, the system processes live video streams captured from a webcam, performing image preprocessing, prediction, and visualization in real time. It overlays recognized traffic signs and confidence scores directly onto the video feed, delivering an efficient solution suitable for deployment on standard computing hardware without GPU acceleration.
Table of Contents
Demo

Components

Hardware

Code Base

Technologies Used

Result

Conclusion

Demo
Demo Video

<p align="center"><b>Demo</b></p>
Demo Photos
<p align="center"> <img src="https://github.com/user-attachments/assets/demo-image-1" width="200" /> <img src="https://github.com/user-attachments/assets/demo-image-2" width="200" /> <img src="https://github.com/user-attachments/assets/demo-image-3" width="200" /> <img src="https://github.com/user-attachments/assets/demo-image-4" width="200" /> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/demo-image-5" width="200" /> <img src="https://github.com/user-attachments/assets/demo-image-6" width="200" /> <img src="https://github.com/user-attachments/assets/demo-image-7" width="200" /> <img src="https://github.com/user-attachments/assets/demo-image-8" width="200" /> </p>
Components
Components Already Developed/Utilized

Component	Description
CNN Model	Custom architecture trained for traffic sign classification
Webcam	Captures live video frames for detection
OpenCV	Handles video capture, image processing, and visualization
TensorFlow/Keras	Deep learning framework used for model development
Data Augmentation Pipeline	Enhances model robustness under varied conditions

Hardware
System Block Diagram



Code Base
Real-Time Video Capture and Processing Code

CNN Model Architecture and Training Code

Preprocessing and Augmentation Scripts

Inference Pipeline with Live Display of Detected Signs

Technologies Used
Python: Core language for data processing and model development.

OpenCV: Used for video streaming, frame manipulation, and drawing overlays.

TensorFlow & Keras: Deep learning frameworks for CNN design and training.

NumPy, Pandas: Used for data handling and analysis.

Matplotlib: For visualizing model performance and dataset distribution.

Result
Project RTS successfully demonstrates high-performance real-time detection of traffic signs:

Achieved ~90% classification accuracy on 43 Indian and German traffic sign classes.

Processes video at near real-time speeds (~30 FPS) on standard laptops without GPU acceleration.

Robust to varied lighting, angles, and occlusion due to comprehensive data augmentation during training.

Clear overlay of detected sign labels and confidence scores on live video, enabling seamless integration into ADAS systems.

Conclusion
Project RTS represents a significant step toward safer and smarter transportation by enabling real-time traffic sign recognition using deep learning. The system is lightweight, scalable, and can be integrated into ADAS frameworks, contributing to accident prevention and improved traffic management. Future improvements may include deployment on embedded platforms, integration with other sensor data, and exploration of advanced detection architectures like YOLO for even faster inference.

The project showcases the power of combining computer vision with deep learning to solve critical real-world problems in the field of intelligent transportation systems.
