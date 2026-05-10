# Home Security Alarm System using PIC16F628A

## Overview
This project implements a simple home security system using PIC16F628A microcontroller and Assembly language.

The system monitors:
- Main door
- Window
- Ventilation
- Balcony door

When motion or intrusion is detected:
- Alarm siren activates
- Pepper gas system activates

The system uses RB4-RB7 interrupt-on-change feature.

## Features
- RB4-RB7 interrupt-on-change
- Real-time intrusion detection
- Alarm activation system
- Sensor monitoring
- Internal oscillator usage
- Assembly language implementation

## Hardware
- PIC16F628A
- Sensors / switches
- LEDs or buzzer
- Resistors

## Pin Configuration

### PORTB Inputs
| Pin | Function |
|---|---|
| RB4 | Main Door Sensor |
| RB5 | Window Sensor |
| RB6 | Ventilation Sensor |
| RB7 | Balcony Door Sensor |

### PORTA Outputs
| Pin | Function |
|---|---|
| RA0 | Siren |
| RA1 | Pepper Gas System |

## Technologies
- PIC16F628A
- Assembly Language
- MPLAB
- Proteus
- Interrupt-on-Change
- Embedded Systems

## Author
Nabil Aktalati
