# Smart-Doors
An IoT-based security solution for automated door access control. Features biometric/RFID authentication, real-time logging, and remote management using C++/Python.

An intelligent access management system designed for enhanced premises security. This IoT solution automates door locking mechanisms based on verified user credentials and maintains a digital access log.

# Key Features
Multi-Factor Authentication: Supports [e.g., RFID, Keypad, or Fingerprint] access.

Real-Time Logging: Tracks all entry/exit attempts with timestamps.

Remote Override: Allows administrators to lock or unlock the door via a mobile app.

Security Alerts: Notifies users of unauthorized access attempts.

# Tech Stack
Microcontroller: ESP32 / Arduino Uno

Language: C++/Python

Components: Solenoid Lock, RFID Module (MFRC522), 16x2 LCD Display

Communication: SPI/I2C Protocols

# Project Structure
├── firmware/           # Logic for sensor reading and lock control

├── schematic/          # Wiring diagram for the locking mechanism

├── logs/               # Sample access log format

└── README.md
# Setup Instructions
​Connect the RFID reader to the SPI pins of the microcontroller.

​Update the AuthorizedUID array in the code with your card IDs.

​Compile and upload the firmware using the Arduino IDE.
