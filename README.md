# Automated-Inventory-Management-System-
Team Project for Shared Services Canada
Smart Shelves Inventory Management System

This project presents an automated inventory management system using smart shelves equipped with ultrasonic and weight sensors. The system enables efficient stock tracking by monitoring product entries, exits, and weight variations on each shelf in real-time.
Project Overview

    Project Type: Automated Inventory Management System
    Team Members:
        Mohamed Boudabbous (300376202)
        Mavie Succar (300059711)
        Ian Bolohan (300310639)
        Josée Danielle Gbotta (300391871)
        Aya Fahim (300326408)
    Technologies Used: Arduino, Thunkable, ultrasonic sensors, weight sensors

System Components
1. Ultrasonic and Weight Sensors

    Ultrasonic Sensors: Detect entries and exits, offering high reliability and ease of integration with Arduino.
    Weight Sensors: Track stock levels by measuring weight changes, ensuring accurate inventory data.

2. Smart Shelves Construction

    Designed in MDF with laser-cut precision, using Arduino for sensor connectivity.
    Each shelf comprises two plates with embedded weight sensors for stable item placement and data accuracy.

3. Mobile Application Interface

    Built on Thunkable for a user-friendly experience, allowing warehouse managers to monitor stock levels, receive alerts, and access real-time data.

Equipment and Setup

    Arduino IDE: For programming and uploading code to the Arduino board.
    Hardware: Ultrasonic sensors (HC-SR04), weight sensors (HX711), breadboard, jumper wires, and a soldering iron.
    Other Tools: Laser cutter, MDF boards, wood glue for assembly.

How to Set Up

    Hardware Assembly:
        Assemble shelves using MDF and integrate weight sensors between plates.
        Mount ultrasonic sensors in designated positions to monitor entry and exit points.

    Arduino Programming:
        Install Arduino IDE and upload sensor programming code.
        Use the HX711 library for weight sensor calibration, and the NewPing library for ultrasonic sensors.

    Mobile Application:
        Set up the Thunkable application following the design template for real-time notifications.
        Connect to the Arduino system to receive updates on inventory levels.

Testing and Validation

    Weight Sensor Calibration: Ensure accuracy by testing with known weights.
    Ultrasonic Sensor Testing: Verify entry and exit detection by simulating movement in front of the sensors.
    System Monitoring: Use the Thunkable app to validate data consistency and ease of use.

Future Enhancements

    Cloud Integration: Enable remote monitoring by connecting the system to a cloud platform.
    Enhanced Sensors: Improve sensor precision to minimize false alerts.
    User Feedback: Refine the interface based on user feedback for better usability.
