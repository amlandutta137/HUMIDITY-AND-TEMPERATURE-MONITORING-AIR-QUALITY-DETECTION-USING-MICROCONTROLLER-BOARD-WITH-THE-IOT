# HUMIDITY-AND-TEMPERATURE-MONITORING-AIR-QUALITY-DETECTION-USING-MICROCONTROLLER-BOARD-WITH-THE-IOT
The "Humidity, Temperature Monitoring and Air Quality  Detection using Microcontroller Board with IoT" project presents a  comprehensive solution for real-time environmental monitoring. By leveraging  the power of Internet of Things (IoT) technology, the system enables continuous  tracking of temperature, humidity, and air quality.

With a focus on real-time monitoring, this project titled Humidity, 
Temperature Monitoring and Air Quality Detection using Microcontroller 
Board with IoT" project for indoor environments represents a cutting-edge 
solution in the realm of environmental sensing and Internet of Things (IoT) 
technology. This initiative addresses the critical need for monitoring 
indoor air quality, humidity, and temperature in real-time, offering users 
actionable insights to create healthier and more comfortable living or 
working spaces. By integrating advanced sensors, a microcontroller board, 
and IoT connectivity, this project not only ensures precise environmental 
data collection but also facilitates remote monitoring and control for 
enhanced convenience and well-being. The integration of Internet of 
Things (IoT) technology with a microcontroller board allows for real-time 
data acquisition, analysis, and remote monitoring. 
The primary objective of this project is to design a system that monitors 
and provides real-time data on humidity, temperature, and air quality. By 
utilizing a microcontroller board with IoT capabilities, the project aims to 
create a smart and connected solution for environmental monitoring.

MATERIALS USED 

A. ESP 32 --- The ESP32 is a powerful microcontroller board with integrated Wi-Fi and 
Bluetooth capabilities. Its dual-core processor and various built-in peripherals make it an 
excellent choice for IoT applications. ESP32 stands for Espressif32 which is a 
development board developed by Espressif Systems. ESP32 is a 32-bit microcontroller 
equipped with a wireless or Wi-Fi network and Bluetooth Low energy (BLE) using the 
802.11 b/g/n WIFI network protocol that works at a frequency of 2.4 GHz and Bluetooth 
v4. In our project, the ESP32 acts as the brain, collecting data from sensors and facilitating 
communication with the IoT platform.
 

B. MQ135---- This is a MQ 135 Air Quality/Gas Detector Sensor Module for Arduino.
If you are wanting to make a device that is used to detect Ammonia, Sulphide, and Benzene 
steam, also sensitive to smoke and other harmful gasses from the desired distance, then this 
sensor is needed for you. You can buy this sensor from Robu.in at a reasonable price. The 
MQ 135 Air Quality Detector Sensor Module for Arduino has lower conductivity in clean 
air. When the target combustible gas exists, the conductivity of the sensor is higher along 
with the gas concentration rising. Convert the change of conductivity to the corresponding 
output signal of gas concentration. The MQ135 gas sensor has a high sensitivity to 
Ammonia, Sulphide, and Benzene steam, also sensitive to smoke and other harmful gases. 
It is at a low cost and suitable for different applications such as harmful gases/smoke 
detection.

C. MQ7--- CO Carbon Monoxide Coal Gas Sensor Module detects the concentrations of CO 
in the air and outputs its reading as an analog voltage. The sensor can measure 
concentrations of 10 to 10,000 ppm. The sensor can operate at temperatures from -10 to 
50°C and consumes less than 150 mA at 5 V. This module provides both digital and analog 
outputs. The threshold level for digital output can be easily adjusted using the preset on the 
board. The MQ-7 sensor module can be easily interfaced with Micro-controllers, Arduino 
Standard Test Conditions
Temperature: 20°C ± 2°C
Humidity: 65% ± 5% RH
Standard Test Circuit: Vc: 5.0V± 0.1V; Vh(high):5.0V±0.1V Vh(low): 1.5V 0.7V


D. MQ8--- A sensitive material MQ-8 Hydrogen Gas Sensor Module H2 Alarm Detection use 
in clean air low conductivity tin oxide (SnO2). When there is the environment in which the 
combustible gas sensor, conductivity sensor with increasing concentration of combustible 
gases in air increases. Using a simple circuit to convert the change in conductivity of the 
gas concentration corresponding to the output signal. MQ-8 hydrogen gas sensor of high 
sensitivity, the monitoring of the other hydrogen-containing gas is also very satisfactory. 
This sensor can detect a wide range of hydrogen gas, city gas, in particular, is a low-cost 
sensor for a variety of applications. Suitable for home or industrial hydrogen leakage 
monitoring devices. Can not interfere with ethanol vapor, soot, carbon monoxide, and other 
gases.

E. JUMPER WIRES- Jumper wires facilitate the connection between various components 
on the breadboard, allowing for an organized and flexible circuit layout. They play a crucial 
role in establishing electrical connections in the project. Jumper wires are the unsung 
heroes of prototyping., It allowing for a modular and flexible circuit design. The color￾coded wires aid in organizing connections, making it easier to troubleshoot and modify the 
circuit.

F. BREADBOARD - The breadboard is the testing ground for your circuit. It allows you to 
experiment with different configurations without the need for soldering. The layout of 
interconnected holes and rows simplifies the process of building and iterating on your 
project.

G. 3.7V LITHIUM BATTERY - The lithium battery serves as the power source for the 
portable project. Its compact size and high energy density make it suitable for applications 
where space and weight are critical factors. The 3.7V lithium battery is a lightweight and 
rechargeable power source. Its high energy density is particularly advantageous for 
portable projects. In the context of your IoT-based environmental monitoring system, this 
battery provides the necessary energy for the ESP32 and other components.
FIG --- 7 (3.7V LITHIUM BATTERY)
H. BOOST CONVERTER -- The boost converter is a pivotal component for projects where 
the input voltage needs to be increased. In the project, it ensures a stable power supply for 

the ESP32 by boosting the voltage from the 3.7V lithium battery. This is essential for 
maintaining the microcontroller's operational integrity.
 FIG – 8(BOOST CONVERTER)
I. CHARGING MODULE-- The charging module simplifies the recharging process of the 
lithium battery. Its compatibility with USB standards (C/Micro USB) ensures ease of use 
and accessibility. This module not only contributes to the longevity of your project but also 
enhances user convenience.

J. SWITCH -- The switch serves as the user's interface to control the power state of the 
device. It enables users to conserve battery life by turning the system on or off as needed. 
This simple yet crucial component enhances the practicality and energy efficiency of the 
project.

K. LED-- Light Emitting Diode are not just indicators; they are visual storytellers. In the 
project, LEDs can provide instant feedback on the system's status. Whether indicating 
successful data transmission or serving as a power indicator, LEDs enhance the user 
experience by offering a quick and visual understanding of the device's state.

L. DIODE -- Diodes play a protective role in our circuit. For instance, a diode could prevent 
reverse voltage from damaging the components, ensuring the longevity of the system. This 
small but critical component contributes to the reliability and durability of the project.

M. RESISTOR -- Resistors are versatile components used for multiple purposes. In the 
project, they might limit current to LEDs, protecting them from excessive current flow. 
Resistors are essential for maintaining proper voltage levels across different parts of the 
circuit. 

N. DHT11SENSOR -- The DHT11 sensor is the sensory organ of the environmental 
monitoring system. It accurately measures humidity and temperature, providing real-time 
data that forms the basis for environmental analysis. Its compact design and reliability 
make it a popular choice for IoT applications focused on climate monitoring.
