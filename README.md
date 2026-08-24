# Arduino Ultrasonic Distance Indicator with LEDs

A simple Arduino Uno project to measure distance using an HC-SR04 ultrasonic sensor and indicate proximity zones using 3 LEDs.

About :
In this project, an HC-SR04 ultrasonic sensor is used to detect object distances and indicate proximity zones via 3 LEDs (Far: 61 to 90 cm - Green on pin 13, Medium: 31 to 60 cm - Orange on pin 12, Near: 0 to 30 cm - Red on pin 11). The Echo pin is connected to digital pin 2 using external hardware interrupts (`attachInterrupt()`), and the Trigger pin is connected to digital pin 3. The code calculates object distance accurately and updates the indicator LEDs with non-blocking timing.

Components :
- Arduino Uno
- 1 HC-SR04 Ultrasonic Sensor
- 3 LEDs (Green, Orange, Red)
- 3 Resistors (220Ω)
- Breadboard
- Jumper wires

Tools :
- Arduino IDE
- C/C++
- Tinkercad Circuits

A-QITAZ Mechatronics Engineering Student :)
