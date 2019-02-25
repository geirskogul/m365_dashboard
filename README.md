# Xiaomi M365 Display 
# Products Used  
Arduino Nano    
I2C OLED 0.96" Screen     
3d Printed Bracket  
1N4148 Diode  
0.25w 120ohm Resistor       

Estimated Price: $20-40 depending on whether or not you're using a clone Arduino

# Flashing  
Install the libraries provided in the files, install them to your 
arduino libary folder, usually C:\Users\%username%\Documents\Arduino\libraries.
I used Arduino 1.6.6, but newer versions should work.  Will not work with 
Arduino versions prior to 1.4.3.
https://www.arduino.cc/en/Main/OldSoftwareReleases  

# Physical Connections  
![alt text](https://i.imgur.com/FpdTOOb.png)  

# Known Issues  
Sometimes, especially on hard braking, the Arduino freezes.  I am unsure of how
to fix this, and the reset button does not fix it.  I recommend installing a NC 
button to reset the Arduino on the +5V line, or simply stopping the scooter
and restarting it.

# 3D Printed Case
I am currently working on an updated 3D printed case design that fits the Nano,
when that design is finished I will link it here.
