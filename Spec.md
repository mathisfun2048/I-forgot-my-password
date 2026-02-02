# Specifications

This document so I can outline what I want this to achieve

I want this to be a USB HID device for selecting and injecting predefined text snippets into a host computer


# Hardware Configuration

MCU = RP2040
Flash = 2MB
Clock = 125MHz

pinout:

| Component | Signal | Gpio|
|---        | ---     |---|
| OLED | SDA, SCL | 4, 5|
|Switch| Input | 1 |
|Encoder| A, B, Switch | 26, 28, 27|


# Memory Layout

## Flash map

