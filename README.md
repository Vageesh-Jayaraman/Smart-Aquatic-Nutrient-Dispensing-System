# Smart Aquatic Nutrient Dispensing System

## Overview

This project implements a smart aquatic nutrient dispensing system to automate fish feeding and enhance the well-being of aquatic inhabitants. The system employs various components including NodeMCU 8266, continuous rotation 360° servo motor, WS2818 LED strip, photodetector, submersible ultrasonic sensor, and a hopper or container for pet food. 

### Components Used

1. **NodeMCU 8266:**
   - Among all WiFi modules, NodeMCU stands out for its integrated ESP8266 module, providing cost-effective wireless connectivity, ease of programming with Arduino IDE, a compact design, scalability through Lua scripting, and a substantial number of GPIO pins.

2. **Continuous Rotation 360° Servo Motor:**
   - This is used for rotating the Archimedes screw. It has integrated motor drivers in a compact and inexpensive way. It can easily drive from the microprocessor itself not needing an external power supply. It also provides high torque. A continuous rotation servo motor can also be controlled by the function servo.writeMicroseconds(), which by default accepts values from 1000-2000.

3. **WS2818 LED Strip:**
   - We chose the WS2818 LED strip for vibrant lighting, as it allows programmable and customizable colors, promoting a visually engaging environment for fish. Adequate lighting is crucial for fish health, influencing their circadian rhythm, mood, and overall well-being, and the WS2818 strip ensures optimal illumination tailored to their needs.

4. **Photodetector:**
   - The photodetector is employed to detect ambient light levels, enabling the automated fish feeding system to distinguish between day and night. This ensures precise control over feeding schedules, aligning with the natural circadian rhythm of the fish for optimal health and behavior.

5. **Submersible Ultrasonic Sensor:**
   - The submersible ultrasonic sensor helps monitor fish behavior by detecting their proximity to the water's surface. Setting a threshold allows the system to recognize when fish gather near the top, signaling hunger, and triggers the automated feeding process, ensuring timely and responsive care for the aquatic inhabitants. This approach optimizes feeding efficiency and promotes the well-being of the fish.

### Integration with Blynk IoT

This project integrates with the Blynk IoT platform for mobile app connection, enabling remote monitoring and control of the aquatic nutrient dispensing system. The Blynk app interface allows users to adjust feeding schedules, monitor environmental parameters, and receive notifications, ensuring seamless interaction with the system.

[Blynk IoT](https://blynk.io)

### Circuit Diagram
<img width="721" alt="image" src="https://github.com/Vageesh-Jayaraman/Smart-Aquatic-Nutrient-Dispensing-System/assets/143870355/9f805412-e285-4623-8c5d-a0d7f1ce60a2">

### Arduino Code and Working Video
#### [Arduino Code](Arduino_Code.txt)
#### [Working Video](Working_Video.mp4)





