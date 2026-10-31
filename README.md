# Embedded-Sensor-Data-Acquisition-and-Monitoring-System
This repository contains the circuit design, hardware configuration, and source code for an embedded monitoring system. The system integrates analog and digital sensors to gather environmental or physical parameters, processes the data through a microcontroller unit, and drives output actuators or indicators accordingly.

🔌 System Architecture & Components
The hardware setup comprises the following key modules:

Microcontroller / Core Processing Unit: Acts as the central brain managing sensor polling, data processing, and peripheral communication.

Infrared (IR) Sensor Module: Utilized for object detection, proximity sensing, or motion-based tracking.

MQ-2 Gas Sensor Module: Detects combustible gases, smoke, or air quality variations, providing both analog (AOUT) and digital (DOUT) outputs.

Ultrasonic Sensor (HC-SR04): Measures precise distance and liquid/object level detection via trigger (US_TRIG) and echo (US_ECHO) pins.

Motor Driver (L293D / U1 & U2): Facilitates bidirectional DC motor control and stepper motor operations (STEP1 through STEP4).

Power Supply Unit: Regulated dual-rail power distribution (Main Supply: 5V, Step Power: 12V) to safely power logic circuits and heavy inductive loads (motors).

📐 Circuit Diagram
The comprehensive schematic of the embedded system wiring layout is stored in the repository:

File Path: Circuit diagram..png

🚀 Getting Started
Prerequisites
Simulation software or IDE compatible with your microcontroller target (e.g., Arduino IDE, MPLAB, or Proteus Design Suite for schematic verification).

Required hardware components listed in the circuit diagram.
