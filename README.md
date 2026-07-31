# ESP32-Smart-Medicine-Reminder
An IoT-based Smart Medicine Reminder built with ESP32 that reminds users to take medicines on time using scheduled alerts, Wi-Fi notifications, and a simple monitoring system. Designed to improve medication adherence and patient safety.

Project Overview
This project is an IoT-based Smart Medicine Reminder and Automatic Pill Dispenser using an ESP32. At the scheduled time, the system displays medicine details on an OLED, activates a buzzer and LED, and automatically opens the correct pill compartment using a servo motor. The user confirms medicine intake by pressing a button. If no confirmation is received, the system sends a notification to the caregiver and stores the medication status in Firebase/Blynk.

Features
Scheduled medicine reminders
Automatic pill dispensing
OLED medicine display
Buzzer and LED alerts
One-button confirmation
Missed dose detection
Caregiver notifications
Cloud-based medication history

Hardware
ESP32, DS3231 RTC, OLED Display, SG90 Servo, Push Button, Buzzer, LED, Wi-Fi.

Software
Arduino IDE, ESP32 Board Package, Firebase/Blynk, RTClib, Adafruit SSD1306, ESP32Servo.

Future Improvements
Multiple medicine compartments
Mobile app for schedule management
Voice reminders
Battery backup
SMS alerts using GSM
AI-based medicine adherence analysis

This design is simple enough for a college prototype while demonstrating key IoT, embedded systems, and automation concepts.
