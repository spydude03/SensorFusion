# SensorFusion

## 1. Installing pip packages  
First, we need to install python libraries. Make sure you that you are using PYTHON 3.7:  
+ djitellopy == 1.5
+ numpy == 1.19.3
+ opencv-python == 4.5.1.48
+ mediapipe == 0.8.2
 
## 2. Connection test  
First, connect dji tello drone, then run the "drone connection test.py" python file.  

**On successful connection you will see:**  

1. Connection test:  
   Send command: command  
   Response: b'ok'  

2. Video stream test:  
   Send command: streamon  
   Response: b'ok'  

**If connection fails, you will see:**  

1. Connection test:  
   Send command: command  
   Timeout exceed on command command  
   Command command was unsuccessful. Message: false  

2. Video stream test:  
   Send command: streamon  
   Timeout exceed on command streamon  
   Command streamon was unsuccessful. Message: false  

## 3. Main part  
If everything is okay and you don't have any problems, open "main.py" and run this code.

## 4. Gestures

| **Finger Count** | **Drone Action** | **Code** |
|-----------------|-----------------|----------|
| 0              | Land            |          |
| 1              | Move Forward    |          |
| 2              | Move Backward   |          |
| 3              | Move Left       |          |
| 4              | Move Right      |          |
| 5              | Takeoff         |          |
