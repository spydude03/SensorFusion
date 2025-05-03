# SensorFusion

1. Installing pip packages
  First, we need to install python libraries. Make sure you that you are using PYTHON 3.7:
  djitellopy == 1.5
  numpy == 1.19.3
  opencv_python == 4.5.1.48
  mediapipe == 0.8.2

2. Connection test
  First, connect dji tello drone, then run the "drone connection test.py" python file
  On successful connection i will see:
    1. Connection test:
  Send command: command
  Response: b'ok'
    2. Video stream test:
  Send command: streamon
  Response: b'ok'

  If you get such output, you need to check your connection with the drone
    1. Connection test:
  Send command: command
  Timeout exceed on command command
  Command command was unsuccessful. Message: False
    2. Video stream test:
  Send command: streamon
  Timeout exceed on command streamon
  Command streamon was unsuccessful. Message: False
