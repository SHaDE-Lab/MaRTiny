# MaRTiny

This is the wiki for all things related to the MaRTiny

All the code can be found at [https://github.com/MaRTiny-SHaDELab](https://github.com/MaRTiny-SHaDELab)

- [MaRTiny-ESP32](https://github.com/MaRTiny-SHaDELab/MaRTiny-ESP32) Contains the code for uploading to the ESP32-CAM
- [MaRTiny-Arduino](https://github.com/MaRTiny-SHaDELab) Contains the code for the Arduino
- [MaRTiny-server](https://github.com/MaRTiny-SHaDELab/MaRTiny-server) Server code (Python Flask) for receiving images from ESP-32 CAM, run YOLO object detection and shadow segmentation
- [MaRTiny-edge](https://github.com/MaRTiny-SHaDELab/MaRTiny-edge) Server code (Node.js express) for receiving, storing, and returning the sensor data
- [MaRTiny-view](https://github.com/MaRTiny-SHaDELab/MaRTiny-view) Website code for displaying MaRTiny data. It gets data from MaRTiny-edge

## System Diagram

![MaRTinyArch](https://github.com/SHaDE-Lab/MaRTiny/assets/34399297/02648afe-1179-4989-9722-450a5aa19c06)

