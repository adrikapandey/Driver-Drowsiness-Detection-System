# Driver-Drowsiness-Detection-System

The Driver Drowsiness Detection System is a real-time, AI-powered safety application designed to monitor a driver's facial and eye movements to detect signs of drowsiness. This project leverages deep learning and computer vision techniques to analyze live webcam footage, focusing primarily on the eyes and facial expressions. A custom-built Convolutional Neural Network (CNN) model is trained to classify whether the driver’s eyes are open or closed. When the system detects prolonged eye closure beyond a defined threshold (e.g., 2 seconds), it triggers an audio alert to wake the driver and prevent potential accidents.

The system is built using **Python** and integrates several powerful libraries including **TensorFlow**, **Keras**, and **OpenCV**. To ensure accuracy and reliability in varied lighting conditions, techniques like **histogram equalization** and **ensemble modeling** are implemented. The model processes real-time frames using OpenCV, while the front-end interface is deployed using **Flask** and **Streamlit**, allowing for real-time monitoring and alerts. Data is preprocessed using **NumPy**, and model performance is evaluated with metrics like confusion matrices and accuracy scores.

Key Features

* Real-time video stream analysis using OpenCV**.
* Custom CNN model** for eye-state classification (open/closed).
* Histogram equalization to improve accuracy under different lighting conditions.
* Ensemble techniques to enhance model robustness and reduce false positives.
* Audio alert system using **Flask** to warn the driver if drowsiness is detected.
* Seamless deployment using **Streamlit** for interactive UI and monitoring.
* Preprocessing and evaluation using NumPy, Adam optimizer**, and confusion matrix.

Real-Life Applications

* Automobile Safety Systems**: Integration into modern vehicles to alert drowsy drivers in real time.
* Fleet Management**: Monitoring commercial drivers during long-haul trips to reduce accidents.
* Public Transport Monitoring**: Enhancing safety in buses, trains, and taxis by ensuring drivers remain alert.
* Driver Training Simulators**: Used in training modules to educate drivers on the dangers of fatigue.
* Wearable Tech Integration**: Can be adapted into glasses or headsets for portable alert systems.

This project highlights the powerful combination of deep learning and computer vision to address real-world problems. It not only showcases technical skills in AI and software deployment but also demonstrates how technology can be used to save lives by preventing fatigue-related road accidents

