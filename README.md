# IOT-based-Smart-Stick


An affordable and efficient assistive device designed to improve navigation and safety for visually impaired individuals. This smart stick uses an ultrasonic sensor to detect nearby obstacles and alerts the user through sound and light feedback.

## Overview

This smart stick integrates ultrasonic sensing and microcontroller logic into a lightweight, portable form—providing real-time alerts to improve spatial awareness.

## Objectives

- Detect obstacles within 5 cm using ultrasonic sensing.
- Alert the user through both a buzzer and an LED.
- Provide a portable, rechargeable power supply.
- Keep the solution lightweight, low-cost, and easy to replicate.

## Components Used

| Component                 | Description                                                       |
|--------------------------|-------------------------------------------------------------------|
| Arduino UNO              | Controls sensor readings and outputs                             |
| HC-SR04 Ultrasonic Sensor| Measures distance to obstacles using ultrasonic waves             |
| DC Buzzer                | Sounds when an object is detected within range                    |
| LED Diode                | Lights up with the buzzer as a visual alert                       |
| PVC Pipe                 | Stick body that houses all components                             |
| Jumper Wires             | Connect components to the Arduino                                 |
| 9V Rechargeable Battery  | Powers the entire system                                          |
| Cable Tie Clips          | Securely attaches components to the stick                         |

## Working Principle

1. The HC-SR04 ultrasonic sensor emits ultrasonic waves.
2. When these waves hit an obstacle, they reflect back to the sensor.
3. The Arduino UNO calculates the time taken for the waves to return and converts it into distance.
4. If the distance is 5 cm or less:
   - The buzzer emits a sound.
   - The LED turns on.
5. If no obstacle is within range, both alerts remain off.

This provides real-time detection of upper-body level obstacles, enhancing user safety.

## Arduino Code

The Arduino sketch reads data from the ultrasonic sensor and triggers alerts accordingly.  
Refer to `smart_stick.ino` for the complete code.

## Features and Benefits

- Dual alert system: sound and light
- Lightweight and ergonomic design
- Cost-effective and easy to build
- Can be expanded with GPS, Bluetooth, or voice assistance

## Applications

- Navigation support for visually impaired individuals
- Educational project in embedded systems and assistive technology
- Low-cost prototype for mobility aid development

## Conclusion

The Smart Stick demonstrates how basic electronics and sensors can be used to create meaningful, real-world assistive technology. This prototype improves awareness of obstacles beyond the reach of traditional mobility tools and lays a strong foundation for future enhancements.


