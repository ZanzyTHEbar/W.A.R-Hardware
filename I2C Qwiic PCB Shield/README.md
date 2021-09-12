# 🔹🔹  Wifiu Assisted Reality 🔹 🔹 

# W.A.R

This repo is dedicated to the **DIY** Android based *Augmented Reality Headset*. 

# WHAT IS THIS PROJECT

Running on Android 8.1 with 4 cameras and an iTOF sensor, this headset will leverage ARCore and open source Deep Learning algorithms to provide a custom personal assistant Waifu. 

W.A.R will come pre-installed to all headsets. 

Developer access and an SDK are available upon request. 

# Current Headset Concept image:

![9213731621368454357](https://user-images.githubusercontent.com/45744329/132788308-64695ec7-a591-4c35-ba48-dc03ebebf283.png)

# Inspirations 

https://hackaday.io/project/179843-low-cost-augmented-reality-vr-for-microcontroller

https://hackaday.com/2021/09/02/a-microcontroller-friendly-ar-headset-on-the-cheap/?fbclid=IwAR1XItgtUjLt92cfcjPFwVwjDEH6s6WtJNDr8hJExN8CSCi_0-b47x9F5A4


# BOM

You will need to purchase a few compents before you begin: 

__*Materials for purchase*__

1. Orange Pi 4B - (https://orangepi.com/index.php?route=product/category&path=238_242 , http://www.orangepi.org/Orange%20Pi%204B/ , https://orangepi.com/index.php?route=product/product&product_id=880)
   1. x2 18MP Camera Modules (remove filters for IR) x1 Stereo Binocular Camera (https://www.amazon.com/IMX219-83-Stereo-Binocular-Camera-Application/dp/B087P9VHJN/ref=sr_1_3?dchild=1&keywords=stereo+camera&qid=1630202995&s=electronics&sr=1-3)

2. Accelerometer Magnetometer (https://www.amazon.com/SparkFun-Breakout-ICM-20948-connection-Accelerometer-Magnetometer/dp/B07VNV3WKL/ref=sr_1_3?dchild=1&keywords=IMU&qid=1630202386&sr=8-3)

3. GPS Module (https://www.amazon.com/dp/B07P8YMVNT?tag=gaming007a5-20&linkCode=osi&th=1&psc=1&keywords=Best%20Arduino%20GPS%20Modules)

4. 6" 2560x1440 display (https://www.amazon.com/Monitor-Printer-Projector-Display-2560x1440/dp/B0826YHTLM/ref=sr_1_4?dchild=1&keywords=6+inch+2k+LCD+display&qid=1630205512&s=electronics&sr=1-4)

5. TOF sensor (https://www.kiwi-electronics.nl/nl/adafruit-vl53l0x-time-of-flight-distance-sensor-30-to-1000mm-stemma-qt-2866) 

# Code


# HOW TO ORDER PCBS

PCBS can be ordered from JLCPCB or PCBWay, or made yourself. The PCB files are still in prototype phase and i welcome any development ideas. 

Files include: 

1. Bill of Materials - BOM 
2. Gerber files
3. Pick and Place files (though this is really just an I2C breakout HAT for the Orange Pi 4B) 

# HOW TO SETUP

Setup is very straight forward, thankfully. 


__*SETUP*__

1. Acquire PCB and sensors. 
2. Assemble per the schematics included in this repo 
3. Plug the sensors into the Orange Pi HAT - take note that 2 Qwiic connects are 3V while only 1 is 5V


