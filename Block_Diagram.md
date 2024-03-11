# Team's Block Diagram

The block diagram consists of:
<br>
1. One TC74 Temperature Sensor
   - This temperature sensor can accurately read the temperature from about -40°F to 257°F

2. One Humidity Sensor
   - This humidity sensor can read relative humidity as a percentage
   - The sensor has an accuracy of +- 4.5%
  
3. One High Powered 12v Motor
   - This motor will be used to present the canopy and retract based off temperature and humidity values
   - Motor itself will receive power from the 12 volt rail as the motor driver will recieve 3.3V
  
4. The entire system is programmed through a PIC18F47Q10 Microchip along with an ESP32 WiFi Module
   - This Microcontroller is based on a 8-bit architecture making it a low power consumption.
   - Is well suited for a wide range of embedded control applications.
  
### The Current Block Diagram:
<br>

![image caption](Pictures/BD(2).png)
