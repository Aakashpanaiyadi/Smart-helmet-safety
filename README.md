# Smart-helmet-safety


Description of Smart Helmet Code

This program is developed for a Smart Helmet System using a PIC microcontroller, LCD display, GSM module, sensors, and motor control. The main objective of this system is to ensure rider safety by allowing vehicle ignition only when safety conditions are satisfied and to provide alerts and emergency communication.

System Overview

The smart helmet system checks the following conditions before allowing the vehicle to start:

Helmet worn (HL)

Alcohol detection (GS – Gas sensor)

Key presence (KY)

Fuel level monitoring

Emergency location sharing via GSM

Countdown safety delay

The system displays appropriate messages on a 16×2 LCD and controls the motor (MTR) accordingly.

Hardware Components Used

PIC Microcontroller

16×2 LCD Display

Alcohol/Gas Sensor (GS)

Helmet Detection Switch (HL)

Key Switch (KY)

Fuel Level Sensor (ADC input)

GSM Module (UART)

Motor / Relay

Push Buttons (sw, sw1)

Pin Configuration

RC0, RC1, RC2 → LCD control pins (RS, RW, EN)

PORTD → LCD data pins

RB4 → Gas sensor (alcohol detection)

RB5 → Helmet sensor

RB6 → Key detection

RC4 → Motor control

RB0, RB1 → Switches
