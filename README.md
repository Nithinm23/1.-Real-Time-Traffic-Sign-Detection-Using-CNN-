# Project RTS - Real-Time Traffic Sign Detection Using CNN

# Overview
<p align="justify">
Project RTS is an advanced real-time traffic sign detection and recognition system designed to enhance road safety and support intelligent transportation solutions. Leveraging deep learning and computer vision, the system identifies and classifies traffic signs from live video feeds, providing instant feedback crucial for driver assistance systems and autonomous vehicles. The model is trained on diverse datasets of Indian and German traffic signs to ensure robust performance across various conditions.
</p>

# Abstract
<p align="justify">
Project RTS implements a real-time pipeline for detecting and classifying traffic signs using a custom Convolutional Neural Network (CNN) architecture. Trained on approximately 35,000 labeled images covering 43 classes, the system processes live video streams captured from a webcam, performing image preprocessing, prediction, and visualization in real time. It overlays recognized traffic signs and confidence scores directly onto the video feed, delivering an efficient solution suitable for deployment on standard computing hardware without GPU acceleration.
</p>

# Table of Contents
- [Demo](#Demo-Photos)
- [Components](#Components)
- [Hardware](#Hardware)
- [Code Base](#Code-Base)
- [Technologies Used](#Technologies-Used)
- [Result](#Result)
- [Conclusion](#Conclusion)

## Demo Photos

<p align="center">
  <img width="661" height="506" alt="Screenshot 2025-04-27 180606" src="https://github.com/user-attachments/assets/64001106-f329-41bc-85d2-ebc5db2457fc" />
</p>

# Libraries
Libraries Already Developed/Utilized

| Libraries | Description |
| :---         | :---      |
| CNN Model | Custom architecture trained for traffic sign classification |
| Webcam | Captures live video frames for detection |
| OpenCV | Handles video capture, image processing, and visualization |
| TensorFlow/Keras | Deep learning framework used for model development |
| Data Augmentation Pipeline | Enhances model robustness under varied conditions |

# Block Diagram
System Block Diagram

[System Block Diagram]<img width="875" height="545" alt="Screenshot 2025-05-21 164759" src="https://github.com/user-attachments/assets/f0f1a23b-1b0c-4acc-beba-cbd44d1f2107" />

# Code Base
- Real-Time Video Capture and Processing Code
- CNN Model Architecture and Training Code
- Preprocessing and Augmentation Scripts
- Inference Pipeline with Live Display of Detected Signs

# Technologies Used
1. Python: Core language for data processing and model development.
2. OpenCV: Used for video streaming, frame manipulation, and drawing overlays.
3. TensorFlow & Keras: Deep learning frameworks for CNN design and training.
4. NumPy, Pandas: Used for data handling and analysis.
5. Matplotlib: For visualizing model performance and dataset distribution.

# Result
Project RTS successfully demonstrates high-performance real-time detection of traffic signs:

- Achieved ~90% classification accuracy on 43 Indian and German traffic sign classes.
- Processes video at near real-time speeds (~30 FPS) on standard laptops without GPU acceleration.
- Robust to varied lighting, angles, and occlusion due to comprehensive data augmentation during training.
- Clear overlay of detected sign labels and confidence scores on live video, enabling seamless integration into ADAS systems.

# Conclusion
Project RTS represents a significant step toward safer and smarter transportation by enabling real-time traffic sign recognition using deep learning. The system is lightweight, scalable, and can be integrated into ADAS frameworks, contributing to accident prevention and improved traffic management. Future improvements may include deployment on embedded platforms, integration with other sensor data, and exploration of advanced detection architectures like YOLO for even faster inference.

The project showcases the power of combining computer vision with deep learning to solve critical real-world problems in the field of intelligent transportation systems.
