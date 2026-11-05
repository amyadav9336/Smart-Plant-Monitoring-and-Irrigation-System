Smart Plant Monitoring and Irrigation System
Arduino UNO source code

Included file:
Smart_Plant_Irrigation.ino

Connections:
- Soil moisture sensor analog output -> Arduino A0
- Relay module IN -> Arduino digital pin 8
- Connect sensor and Arduino grounds together.

Notes:
- This code assumes an active-LOW relay module.
- Pump turns ON when the sensor reading is above 600.
- Pump turns OFF when the sensor reading is below 400.
- Adjust DRY_VALUE and WET_VALUE after testing your sensor.
- Use a suitable external power supply for the pump. Do not power the pump directly from an Arduino pin.
