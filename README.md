# Sand Battery System
# Project Overview
This project is a Sand Battery System designed to store energy in the form of heat using sand. The embedded system, powered by Arduino, ensures safe operation by continuously monitoring the temperature using a Dallas temperature sensor. When the temperature exceeds a threshold of 110°C, the system automatically cuts off the heating source to prevent overheating.

# Components Used
* Arduino Uno (or any compatible board)
* Dallas DS18B20 Temperature Sensor - for temperature monitoring
* Power Relay Module - for controlling the heating source
* Heating Element - used to store energy in sand as heat
* Sand Storage Unit - to retain heat
* Power Supply - for the Arduino and heating element
# System Workflow
1) Temperature Monitoring: The Dallas DS18B20 temperature sensor continuously monitors the temperature within the sand storage unit.

2) Temperature Control: When the temperature reaches 110°C, the Arduino sends a signal to the relay module to cut off the power to the heating element, preventing further heating.

3) Real-Time Control: The system continuously monitors the temperature, turning the heating element back on when the temperature falls below the threshold, ensuring a stable and safe operation.
