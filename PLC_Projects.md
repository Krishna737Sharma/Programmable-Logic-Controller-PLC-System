# PLC_Projects
This repository contains several projects that I have completed to enhance and hone my PLC programming skills.

### [BasementLightControl](/BasementLightControl)

![basementlightdemo](https://github.com/user-attachments/assets/b043e62e-1bf6-42a3-a0bc-424e45f79f1b)

# BasementLightControl

### Table of Contents 
1. [Folder Structure](#folderstructure)
2. [Purpose](#purpose)
3. [Tools Used](#toolsused)
4. [Demo](#demo)

### Folder Structure <a name="folderstructure"></a>
```
BasementLightControl

|---images (all images for README.md file)
|---|---basementlightdemo.gif (program demo)

|---src (source code)
|---|---BasementLightControl.zap16 (PLC & HMI Code for V16)

|---TIAPortalScreenshots.pdf (TIA screenshots of PLC & HMI programming)
|---README.md (helpful readme file)
```

### Purpose <a name="purpose"></a>
To implement a 3-way switch control logic in a PLC program for a Basement Control Light System. There are two switches: one for upper-level and one for lower-level. Both of the switch control the Basement light. When both of the switches are in the same position, the light must be OFF, when one switch is ON and the other is OFF, then only the light is OFF. Below is a Truth table describing the logic.</br>
| Upper Level Switch | Lower Level Switch | Light Output |
|:------------------:|:------------------:|:------------:|
|         OFF        |         OFF        |      OFF     |
|         OFF        |         ON         |      ON      |
|         OFF        |         ON         |      ON      |
|         ON         |         ON         |      OFF     |

### Tools Used <a name="toolsused"></a>
1. SIMATIC STEP 7 (TIA Portal V16) </br>
2. WinCC RT Advanced (TIA Portal V16 option) </br>
3. PLCSIM </br>


### [SortingPlant](/SortingPlant)

![sortplant_constantspeed_demo](https://github.com/user-attachments/assets/df0f040c-c35b-4456-925c-d16d69773271)

### [TrafficLightControl](/TrafficLightControl)

![trafficlightdemo](https://github.com/user-attachments/assets/16cf5542-7f4d-4932-acdc-19744500a1f4)

### [IoTProjects](/IotProject)

![01_getTime](https://github.com/user-attachments/assets/2defccab-89e1-4cf8-86a1-8e29aac7c722)

</br>
</br>
<p align="center">
  <img src="IotProject/images/02_S7Communication.gif"/>
  <b>S7 Communication Demo</b>
</p>
</br>
</br>
<p align="center">
  <img src="IotProject/images/03_opcua.gif"/>
  <b>OPC-UA Communication Demo</b>
</p>
</br>
</br>
<p align="center">
  <img src="IotProject/images/04_mqtt.gif"/>
  <b>MQTT Communication Demo</b>
</p>
</br>
</br>
<p align="center">
  <img src="IotProject/images/05_python.gif"/>
  <b>Running Python Script Demo</b>
</p>
</br>
</br>
<p align="center">
  <img src="IotProject/images/06_cppoeecalculator.gif"/>
  <b>Running C++ App Demo</b>
</p>
</br>
</br>
<p align="center">
  <img src="IotProject/images/07_mindsphere.gif"/>
  <b>MindSphere Cloud Connection Demo</b>
</p>
