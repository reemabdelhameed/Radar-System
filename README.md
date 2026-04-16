Radar Detection System (Ultrasonic + Servo)

Overview
A radar-based object detection system built using a PIC microcontroller that scans its surroundings using an ultrasonic sensor mounted on a servo motor. The system detects objects within a 180° range and provides real-time visual and audio feedback.


Features
- 180° scanning using a servo motor  
- Object detection using an ultrasonic sensor  
- Real-time display of detection status and angle on an LCD  
- Audio alert using a buzzer upon object detection  
- Continuous real-time scanning and feedback  


Components & Tools
Hardware
- PIC16F877A Microcontroller  
- Ultrasonic Sensor (HC-SR04)  
- Servo Motor  
- LCD Display  
- Buzzer  

Software & Tools
- MPLAB IDE  
- PICkit Programmer  
- Embedded C  


System Functionality
1. The servo motor sweeps from 0° to 180° and back continuously  
2. The ultrasonic sensor measures distance at each angle  
3. The PIC microcontroller processes the data in real time  
4. When an object is detected within a defined threshold:  
   - The LCD displays detection status and angle  
   - The buzzer is activated  
5. The system repeats the scanning cycle continuously
   

Team
- Reem Abdelhameed  
- Omar Sabla


Key Learning Outcomes
- Embedded systems development using PIC microcontrollers  
- Interfacing sensors and actuators with microcontrollers  
- Real-time signal processing and control  
- Hardware-software integration and debugging  


Status
Developed as part of the Programming Elements for Electrical Engineering course at the American University in Cairo (AUC)
