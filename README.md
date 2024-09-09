# Obstacle Detection Using Arduino

This mini-project involves creating an obstacle detection system using an Arduino. The system is equipped with ultrasonic sensors to detect obstacles and provides feedback through a DFPlayer Mini MP3 module and a vibration motor.

## Components Used

- **Arduino Uno**
- **Breadboard**
- **DFPlayer Mini MP3 Player Module**
- **Vibration Motor**
- **Jumper Wires**
- **2 Ultrasonic Sensors**
- **3.5 mm Jack Audio**

## How It Works

The obstacle detection system uses two ultrasonic sensors to detect obstacles on the left and right sides. When an object is detected within a predefined distance, the system provides:

- **Audio Feedback**: The DFPlayer Mini plays an audio file to indicate the presence of an obstacle.
- **Vibration Feedback**: The vibration motor activates to provide tactile feedback.

### **Optional Configuration**

The project is implemented using only two ultrasonic sensors. However, an additional sensor can be added to the center (using pins 4 and 5 on the schematic). If you choose to add this third sensor, you will need to make modifications to the code to accommodate it.

![Photo1](https://raw.githubusercontent.com/AssanAbboud1/Arduino-Project/main/Photo1.png)

![Photo2](https://raw.githubusercontent.com/AssanAbboud1/Arduino-Project/main/Photo2.png)