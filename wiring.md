# ESP32 Wiring Connections

## PN532 NFC Module → ESP32
- SDA → GPIO 21  
- SCL → GPIO 22  
- VCC → 3.3V  
- GND → GND  

## LCD Display (I2C)
- SDA → GPIO 21  
- SCL → GPIO 22  
- VCC → 5V  
- GND → GND  

## Red LED
- Anode → GPIO 13 (via 220Ω resistor)  
- Cathode → GND  

## Buzzer
- Signal → GPIO 15  
- VCC → 3.3V  
- GND → GND  
