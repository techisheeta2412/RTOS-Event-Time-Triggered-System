# RTOS-Based Event-Driven and Time-Triggered Communication System

## Project Overview

This project focuses on the design of a real-time embedded communication system using event-driven and time-triggered communication.

The system was developed for a smart patient-care application where scheduled tasks and emergency events need to be handled efficiently.

## Hardware Used

- STM32F401RE
- ESP32
- Push Button / Alert Interface
- Breadboard and Jumper Wires
- 5V / USB Power Supply

## Software and Tools

- STM32CubeIDE
- Arduino IDE
- PuTTY
- Embedded C
- Arduino C++

## Communication

- MQTT
- Wi-Fi
- UART

## RTOS Concepts Used

- Task Scheduling
- Time-Triggered Tasks
- Event-Driven Tasks
- Message Queues
- Semaphores
- Interrupt Handling
- Inter-Task Communication

## System Working

The STM32 manages real-time tasks using RTOS scheduling.

Time-triggered tasks are used for scheduled medicine reminders and periodic monitoring.

Event-driven tasks are activated when a patient sends an alert or requires immediate assistance.

ESP32 nodes provide wireless communication between the patient unit, nurse unit, and monitoring dashboard using MQTT and Wi-Fi.

## My Contribution

I contributed to understanding and designing the real-time system architecture.

I worked on the separation of periodic and event-driven operations, RTOS task flow, and communication workflow.

I also studied the use of message queues, semaphores, and interrupts for managing multiple embedded tasks and contributed to system testing and technical documentation.

## What Makes This Project Unique

The project combines time-triggered and event-driven communication in a single embedded architecture.

This approach allows periodic tasks to execute at scheduled intervals while critical events can be handled immediately.

The same concept can be applied to UAV and real-time embedded systems where telemetry and sensor monitoring operate periodically while faults or critical events require a fast response.

## Key Learning

- Real-time embedded system design
- RTOS task management
- Event-driven communication
- Time-triggered scheduling
- MQTT and Wi-Fi communication
- STM32 and ESP32 integration
- Embedded system architecture

## Future Scope

- Cloud-based monitoring
- AI-based fault prediction
- Mobile application integration
- Energy-efficient embedded nodes
- Integration with advanced real-time systems

