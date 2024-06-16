# Flight-Control-System

An entirely new flight control system was created. For fixed-wing, autonomous drones, the flight control system is primarily intended to allow them to carry out activities like takeoff, landing, waypoint navigation, payload delivery, etc. on their own.  

This system is entirely composed on first-principles design! This covers a plethora of components, such as the flight simulator, base station, communication protocol, hardware, firmware (using FreeRTOS), control algorithms, and Kalman filtering for state estimation.  

In general, this repository includes:  

Designs for hardware (created with KiCAD).  
Low-level firmware and drivers (FreeRTOS, for the STM32 microcontroller platform).  
higher-level firmware, including control and navigation algorithms, protocols for communication, etc.  
Designs of Kalman filters for state estimation tools for debugging.  
Test algorithms using a flight simulator (both 3-DOF and 6-DOF).  




