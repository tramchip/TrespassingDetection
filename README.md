# TrespassingDetection

Set Up Edge Device
7.1 Hardware Requirements
1. Raspberry Pi 3b + or higher
2. Intel NC2
3. Pi Camera
4. Charger
5. Keyboard, mouse, screen monitor for the initial setup
6. Optional: cases, heatsink, fan, etc.
7.2 Software Setup
7.2.1 Setting up the Raspberry and install the OS and python
• Follow this guide to setup the OS: https://projects.raspberrypi.org/en/projects/raspberrypi-setting-up
• Update the software using sudo apt get or yum install (depends on the
OS)
• Install Python 3
• Optional: setup ssh to monitor your device remotely
7.2.2 Setup Openvino enviroment for ML and computer vision
• follow this guide to install OpenVino on Pi: https://docs.openvinotoolkit.org
7
7.2.3 Ultilize Intel NC2 and start the model training
• install cmake using
$ sudo apt-get install cmake
