# Smoke-Detector
This project implements a smoke detection system utilizing a gas sensor, Arduino microcontroller, DC motor pump, and relay for automated response.

Overview:
Smoke detection is a crucial aspect of fire safety, and this project aims to provide a reliable and cost-effective solution. The system continuously monitors the surrounding environment for the presence of smoke and triggers an alarm or activates an exhaust fan when smoke is detected.

Key Components:
Gas Sensor: A sensitive gas sensor is employed to detect the presence of smoke particles in the air. The sensor provides analog or digital output based on the concentration of smoke particles.
Arduino Microcontroller: The Arduino serves as the brain of the system, processing sensor data and controlling the operation of the DC motor pump and relay. It executes the detection algorithm and triggers appropriate actions upon detecting smoke.
DC Motor Pump: This component acts as an exhaust fan to remove smoke from the environment once detected. The pump is activated by the Arduino when smoke is detected, helping to mitigate the risk of fire.
Relay: The relay is used to control the DC motor pump, enabling the Arduino to switch the pump on and off as needed. It provides isolation between the low-voltage Arduino circuitry and the high-voltage pump.

Functionality:
Continuous Monitoring: The system continuously monitors the surrounding environment for the presence of smoke particles.
Smoke Detection: Upon detecting smoke, the system triggers an alarm and activates the DC motor pump to expel smoke from the environment.
User Interface: The Arduino can be interfaced with a display unit or connected to a computer for real-time monitoring and configuration.

Repository Contents:
Arduino Code: Contains the source code for the Arduino microcontroller, responsible for smoke detection and control of the DC motor pump and relay.
Circuit Image: Provides an image illustrating the connections between the components.

Contributing:
Contributions to this project are welcome! Whether it's bug fixes, feature enhancements, or documentation improvements, feel free to submit pull requests.

Acknowledgments:
Ulluri Naicy (My partner in making this project)
Tharun Reddy (Helped with code)
