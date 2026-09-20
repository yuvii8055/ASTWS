# Automatic Sunlight Tracking Window System (ASTWS)

The Automatic Sunlight Tracking Window System (ASTWS) is a mechatronic, dual-axis solar tracking framework designed to optimize natural indoor lighting and improve building energy efficiency. 

This project utilizes a hybrid tracking methodology to ensure continuous alignment with the sun:
* **Reactive Tracking:** An array of Light Dependent Resistors (LDRs) provides real-time light intensity feedback for active, sensor-driven motor adjustments.
* **Predictive Fallback:** During overcast conditions, the system switches to a power-saving "cloudy mode," relying on a Real-Time Clock (RTC) module and ephemeris calculations to accurately predict solar movement.

### System Architecture
* **Microcontroller:** Logic driven via ESP32 or Arduino.
* **Actuation:** Precision two-axis movement (azimuth and elevation) using NEMA 17 stepper motors and A4988 drivers on a gimbal/yoke mount.
* **Safety Mechanisms:** Integrated limit switches to prevent mechanical over-rotation and ensure secure calibration.

Designed with a focus on sustainable building automation, the ASTWS bridges practical physics with human-centered design to provide a dynamic, smart alternative to static window and lighting systems.
