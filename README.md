# Gas-Leakage-Detector-using-MQ2-Sensor-Arduino-UNO
# Overview

This project is a safety monitoring system designed to detect hazardous gas leaks using an MQ2 gas sensor interfaced with an Arduino UNO. The MQ2 sensor detects gases such as LPG, methane (CH₄), hydrogen (H₂), and propane, and immediately triggers an audible alarm using a buzzer when gas concentration exceeds the safety threshold.

# Features

Detects LPG, CH₄, H₂, and propane using MQ2

Buzzer alarm for real-time leak alert

Simple, low-cost, and reliable gas monitoring

Can be used for home, labs, or industrial safety

Easy to expand with GSM, IoT, or relay modules

# Hardware Components

Arduino UNO

MQ2 Gas Sensor

Active Buzzer

Jumper wires

Breadboard 

Power supply


# Working Principle

The MQ2 sensor continuously monitors the concentration of combustible gases.

When gas levels rise above a safe threshold, the sensor outputs an analog/digital signal.

Arduino UNO reads the sensor output.

If gas concentration is unsafe:

The buzzer turns ON, producing a loud beep to alert people.

The system resets automatically when gas levels return to normal.

# Applications

Home kitchen gas leak detection

LPG cylinder storage safety

Industrial gas monitoring

Car parking areas (CH₄ monitoring)

Safety system for laboratories

# Future Enhancements

Integrate GSM module to send SMS alerts

Add IoT (ESP8266/ESP32) for mobile notifications

Add exhaust fan control using relay

LCD/OLED display for real-time gas readings
