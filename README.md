# ESP32 LDR-Based Human Machine Interface

## About the Project
This project is a simple human-machine interface built using an ESP32 and an LDR sensor. The idea is to create a system that can respond to changes in the surrounding environment, specifically light intensity, and control an output device accordingly.

Instead of manual control, the system automatically adjusts its behavior based on the ambient light, demonstrating a basic form of real-time interaction between a machine and its environment.

---

## Objective
- To design a real-time interactive system using ESP32  
- To measure light intensity using an LDR sensor  
- To control output devices based on sensor input  
- To understand basic human-machine interaction  

---

## Components Used
- ESP32 Microcontroller  
- LDR (Light Dependent Resistor)  
- Resistor (for voltage divider)  
- Servo Motor  
- Breadboard and connecting wires  

---

## Working Principle
The LDR changes its resistance depending on the amount of light falling on it.

- In bright light, resistance decreases  
- In low light, resistance increases  

The ESP32 reads this change as an analog value and processes it to control the output device.

---

## Working
1. The LDR senses ambient light intensity  
2. ESP32 reads the analog value from the sensor  
3. The value is compared with a threshold  
4. Based on the result, the output device is controlled  
   - LED brightness changes or  
   - Servo position adjusts  

---

## Features
- Real-time sensing and response  
- Automatic adjustment based on environment  
- Simple and efficient embedded system design  

---

## Output
(Add your project image here)

Example:
![Output](images/output.jpg)

---

## What I Learned
- Interfacing sensors with ESP32  
- Reading and processing analog data  
- Designing simple control logic  
- Building responsive embedded systems  

---

## Future Scope
- Integration with IoT for remote monitoring  
- Use of more accurate sensors  
- Implementation with RTOS  
- Data logging and analysis  

---

## Author
Sneha Kumari
