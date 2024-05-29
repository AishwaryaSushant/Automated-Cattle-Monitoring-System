# Automated Cattle Monitoring System

Welcome to the Automated Cattle Monitoring System, an advanced tool designed to assist farmers and veterinarians in monitoring cattle health and detecting lumpy skin disease using state-of-the-art computer vision models. This system integrates YOLO for cow detection and Roboflow for lumpy skin disease detection.

## Project Description

The Automated Cattle Monitoring System aims to enhance the health monitoring of cattle by leveraging AI models to detect the presence of cows and diagnose lumpy skin disease. This tool can process both local images and images from URLs, and it also supports real-time detection using a webcam. The system provides an easy-to-use interface for users to upload images or use their webcam for instant detection results.

The system utilizes deep learning techniques in computer vision to detect, label, and count cattle in images and video feeds. Its primary objectives include identifying the presence of animals, categorizing them by type, providing real-time counts, and offering health assessment features for individual animals. 

Additionally, the system incorporates a module to detect lumpy disease in cattle, providing early detection and recommendations for treatment. Through a user-friendly interface, farm owners can interact with the system, access detection results, and receive health assessments for their livestock. 


## About Lumpy Disease

Lumpy skin disease is a viral infection that affects cattle, causing fever, nodules on the skin, and can lead to severe health issues or even death. Early detection and treatment are crucial to prevent the spread of the disease to other animals. This system helps in early diagnosis by analyzing images of cattle and identifying symptoms of lumpy skin disease. 
![img1056](https://github.com/AishwaryaSushant/Automated-Cattle-Monitoring-System/assets/63956495/cba349d8-f3c7-466f-985b-2e17ca277121)

## Project Objectives

The main objectives of this project are to:

1. Detects the presence of cow in images or video feeds.
2. Label the detected animals.
3. Count the number of cows.
4. Provide health assessment for individual animals.
5. Offer suggestions and solutions based on health assessment results.

## Features

- **Cow Detection**: Identify and count cows in an image using the YOLO model.
- **Lumpy Disease Detection**: Detect lumpy skin disease in cattle using a model from Roboflow.
- **Webcam Detection**: Real-time cow detection using a connected webcam.
- **User-Friendly Interface**: A clean and intuitive interface powered by Streamlit.

## User Interface

1. **Cow Detection**:
    - Upload a local image or enter a URL to detect and count cows.

2. **Lumpy Disease Detection**:
    - Upload a local image or enter a URL to diagnose lumpy skin disease.

3. **Webcam Detection**:
    - Use your webcam to detect cows in real-time.

## Working of the Project

1. **Cow Detection**:
    - Uses the YOLO model to detect cows in uploaded images or in frames captured from a webcam.
    - Draws bounding boxes around detected cows and counts the number of cows present in the image or video frame.

2. **Lumpy Disease Detection**:
    - Uses a custom model hosted on Roboflow to analyze images for signs of lumpy skin disease.
    - Displays an emergency alert if lumpy skin disease is detected, advising immediate veterinary attention.

3. **Webcam Detection**:
    - Captures live video feed from the webcam.
    - Uses the YOLO model to detect cows in real-time, displaying bounding boxes around detected cows.

## Libraries Used

- [Streamlit](https://streamlit.io/) for building the web application interface.
- [Pillow (PIL)](https://python-pillow.org/) for image handling.
- [Requests](https://requests.readthedocs.io/) for fetching images from URLs.
- [OpenCV](https://opencv.org/) for image processing and webcam access.
- [Ultralytics YOLO](https://github.com/ultralytics/yolov5) for cow detection.
- [Roboflow](https://roboflow.com/) for lumpy disease detection.
- [Matplotlib](https://matplotlib.org/) for plotting in webcam detection.

## User Interface
![Screenshot (376)](https://github.com/AishwaryaSushant/Automated-Cattle-Monitoring-System/assets/63956495/a0e78b90-8e03-4884-a6ca-ea200c122bc4)

![Screenshot (377)](https://github.com/AishwaryaSushant/Automated-Cattle-Monitoring-System/assets/63956495/0b465154-9b3c-49c4-bbf2-e04d11f3a7d6)

![Screenshot (378)](https://github.com/AishwaryaSushant/Automated-Cattle-Monitoring-System/assets/63956495/4cbce069-dde2-438b-9d24-df59e69e47a4)
