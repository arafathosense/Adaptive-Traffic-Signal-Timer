# Adaptive-Traffic-Signal-Timer

## 📌 Project Overview

The **Adaptive Traffic Signal Timer** is an intelligent traffic management system that dynamically adjusts signal timing based on real-time vehicle detection and traffic analysis. The system leverages Artificial Intelligence (AI), Machine Learning (ML), Deep Learning (DL), and YOLOv8-based object detection to monitor traffic density and optimize green-light duration accordingly.

Unlike traditional fixed-time traffic signals, this system responds to live traffic conditions, reducing congestion, minimizing waiting time, and improving intersection efficiency. The project demonstrates practical implementation of smart-city and intelligent transportation system (ITS) concepts.


## 🎯 Key Objectives

- Real-time vehicle detection using YOLOv8  
- Lane-wise vehicle counting and density estimation  
- Adaptive green-time allocation  
- Congestion-aware signal control  
- Scalable architecture for smart intersections  


## 🧠 System Architecture

### 1️⃣ Vehicle Detection Module
- YOLOv8-based object detection  
- Real-time frame processing  
- Lane-wise vehicle counting  
- Queue-length estimation  

### 2️⃣ Adaptive Signal Control Module
- Dynamic green-time calculation  
- Rule-based traffic prioritization  
- Automated signal switching logic  

### 3️⃣ Visualization & Monitoring
- Real-time detection overlay  
- Traffic count display  
- Adaptive timer visualization  
- Processed output video generation  

**Output:**
<img width="1365" height="727" alt="Screenshot_5" src="https://github.com/user-attachments/assets/70aec7e9-21b8-476e-89a9-317abba57b89" />
<br>
<img width="1365" height="724" alt="Screenshot_6" src="https://github.com/user-attachments/assets/73cf18fd-e265-4273-816a-15d663b46ef3" />
<img width="1365" height="727" alt="Screenshot_7" src="https://github.com/user-attachments/assets/9e40fd94-709e-460e-a1f0-af104f8e3e07" />
<img width="1365" height="725" alt="Screenshot_8" src="https://github.com/user-attachments/assets/765e9d97-7f24-4069-9772-2ab4ed50ac85" />
<img width="1365" height="727" alt="Screenshot_9" src="https://github.com/user-attachments/assets/bf8a10d8-1533-4610-83b7-50acbe1e0f00" />


## 🔬 Future Research Extensions

### 🔹 Multi-Camera Traffic Understanding
Integration of multiple camera feeds across an intersection for improved counting accuracy, duplicate removal, and multi-angle traffic flow monitoring.

### 🔹 Reinforcement Learning for Signal Control
Replacement of rule-based control with reinforcement learning algorithms such as DQN or PPO. Simulation environments like SUMO can be used to train adaptive traffic policies.

### 🔹 Multi-Class Traffic Analysis
Classification and prioritization of different vehicle types (cars, buses, trucks, motorcycles, pedestrians) for more efficient and fair signal allocation.

### 🔹 Weather-Robust Detection
Incorporation of image-enhancement and adverse-weather training techniques to maintain detection accuracy in rain, fog, and low-light conditions.

### 🔹 Edge Deployment on Low-Power Devices
Deployment on edge platforms such as Jetson Nano, Raspberry Pi 5, or Google Coral to enable real-time processing with reduced latency. Model optimization techniques such as pruning and quantization can improve efficiency.

### 🔹 Traffic Flow Prediction
Use of temporal models such as LSTM or GRU to forecast short-term congestion using historical vehicle counts combined with contextual data (time, weather, events).

### 🔹 Accident and Emergency Detection
Integration of anomaly-detection systems to identify accidents, stalled vehicles, or wrong-way driving for automated emergency response.

### 🔹 Green-Wave Optimization
Coordination of multiple intersections to create synchronized “green waves,” reducing congestion and vehicle emissions.

### 🔹 Vehicle Tracking and Speed Estimation
Integration of tracking algorithms (e.g., DeepSORT) to monitor vehicle trajectories, estimate speed, and detect traffic violations.

### 🔹 Digital Twin for Simulation Testing
Creation of a digital replica of intersections using simulation platforms (e.g., SUMO) to evaluate signal strategies before real-world deployment.

## 🛠 Technologies Used

- Python  
- YOLOv8  
- OpenCV  
- TensorFlow  
- NumPy  
- Matplotlib  

## 🎓 Academic & Research Relevance

This project demonstrates:

* Practical application of deep learning in intelligent transportation
* Integration of AI-based perception with adaptive control systems
* Scalability toward smart-city infrastructure
* Research readiness in computer vision, reinforcement learning, and traffic optimization

It provides a strong foundation for advanced research in:

* Artificial Intelligence
* Smart Transportation Systems
* Reinforcement Learning
* Computer Vision
* Urban Traffic Optimization

## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Image Processing**
