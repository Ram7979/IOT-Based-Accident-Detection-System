# IoT-Based Accident Detection and Damage Analysis System using Deep Learning

## Overview

Road accidents are a major cause of fatalities worldwide, often worsened by delays in detection and emergency response. This project presents an **IoT-Based Accident Detection and Damage Analysis System** that leverages **Deep Learning (LSTM + CNN)** to automatically detect vehicle accidents, assess damage severity, and send **real-time alerts** to emergency services.

The system integrates **IoT sensors (accelerometer, gyroscope, GPS)** with **deep learning models** to provide a scalable, intelligent, and cost-effective solution for **smart transportation and road safety**.

This project is also supported by a **published research paper** presented at the *International Conference on Innovations and Research Directions in Science and Technology (ICIRDST-2025)* 

---

## Key Features

* **Real-time accident detection** using sensor-based anomaly detection
* **LSTM-based time-series analysis** for identifying sudden impacts and abnormal motion
* **CNN-based damage severity classification** (Minor / Moderate / Severe)
* **GPS-based location tracking** of accident site
* **Automated email alerts** sent to hospitals and police stations
* **Interactive Streamlit dashboard** for live monitoring and visualization
* **Cloud-ready architecture** for data storage and scalability

---

## System Architecture

The system is designed using a multi-layer architecture:

1. **IoT Sensor Layer**

   * Accelerometer: detects sudden acceleration/deceleration
   * Gyroscope: monitors angular movement and vehicle tilt
   * GPS: captures real-time vehicle location

2. **Data Preprocessing Layer**

   * Noise filtering
   * Normalization of sensor readings
   * Handling missing GPS values

3. **Deep Learning Layer**

   * **LSTM Model**

     * Processes sequential sensor data
     * Detects accident events based on motion anomalies
   * **CNN Model (MobileNetV2 / VGG16)**

     * Analyzes accident images
     * Classifies damage severity
   * **Fusion Layer**

     * Combines LSTM and CNN outputs for final decision

4. **Alert & Notification Layer**

   * Automatically sends email alerts containing:

     * Accident time
     * GPS coordinates
     * Damage severity level

---

## Workflow

1. Continuous data collection from IoT sensors
2. Sensor data preprocessing and normalization
3. Accident detection using LSTM
4. Damage severity analysis using CNN
5. Automatic email alert generation
6. Data logging and visualization on dashboard

---

## Experimental Setup

### Datasets

* **Sensor Data:** 10,000–15,000 time-series samples
* **Image Data:** ~5,000 accident images (minor, moderate, severe)

### Evaluation Metrics

* Accuracy, Precision, Recall, F1-score
* Alert latency
* False positive rate

### Results

* **Accident Detection Accuracy:** >95%
* **Damage Severity Classification Accuracy:** ~92%
* **Fast alert transmission with minimal delay**

---

## Technologies Used

### Hardware

* Raspberry Pi / Arduino
* Accelerometer, Gyroscope, GPS
* Camera module

### Software

* **Python**
* **TensorFlow / Keras**
* **OpenCV**
* **NumPy, Pandas**
* **Streamlit**
* **MongoDB / Firebase**
* **SMTP (Email Alerts)**

---

## Future Enhancements

* Integration with real-time dashcam video feeds
* Nearest ambulance dispatch using GPS
* Large-scale cloud deployment and analytics
* GAN-based data augmentation for improved model performance

---

## Research Publication

**Title:** *IoT-Based Accident Detection System using Deep Learning*
**Conference:** ICIRDST-2025
**ISBN:** 978-93-344-0835-5

---

## Author

**S D V S Ram Naidu**
B.Tech CSE, Lovely Professional University
🔗 GitHub: [https://github.com/Ram7979](https://github.com/Ram7979)
🔗 LinkedIn: [https://linkedin.com/in/sisti-ram-naidu](https://linkedin.com/in/sisti-ram-naidu)

---

*If you find this project useful, feel free to star the repository and contribute!*
