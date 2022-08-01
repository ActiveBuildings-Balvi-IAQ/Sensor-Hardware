# Sensor-Hardware
This repository contains all the necesaary files to develop an IAQ monitoring system that includes CO2 and PM2.5 monitoring

## Sensing Principles
- CO2 is sensed using Non Dispersive Infrared Sensor (NDIR) 
- CO2 is monitored using an MHZ14 NDIR sensor
- PM2.5 is sensed using optical counter method using a laser setup
- PM2.5 is monitored using SDS011 optical counter sensor
- Atmega324 is used as the microcontroller of choice
- The output of the sensing is shown on a OLED/LCD available from Adafruit

## Key to files
- The schematic of the circuitry is in AB1-4.pdf
- The gerbers of the final circuitry is in the IAQ_disp_gerber folder
- Gerber files can be sent to printing directly
- Renders of the PCB is in the Renders folder
