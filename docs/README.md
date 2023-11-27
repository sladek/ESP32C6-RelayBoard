# ESP32C6-RelayBoard
Board with relays and sensors with ESP32C6 SOC.  
[ESP32C6RelayBoard schematic in PDF format](ESP32C6RelayBoard.pdf)

![](ESP32C6RelayBoardSmall.jpg) 
![](ESP32C6RelayBoardBackSmall.jpg) 

**Board contains the following interfaces:**
- 12V DC power connector
- Micro USB for programming/communication
- RGB intelligent LED WS2812b
- 4 x Latching relay 250 VAC, 24 VDC / 16A
- 2 x INA232 Current & Power Monitors & Regulators 48-V, 16-bit high-precision IC output digital power monitor
- 2 x 330V -> 3.3V Voltage divider connected to A/D converter ADC1 of CPU
- 2 x 33V -> 3.3V Voltage divider connected to A/D converter ADC1 of CPU
- 1 x Humidity sensor BME280 measuring relative humidity, barometric pressure and ambient temperature
- Extension connector with the following signals exposed:  
  +5V&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GND  
  UOTXD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; UORXD  
  +3.3V&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GND  
  GPIO4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GPIO5  
  GPIO8&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GPIO9  
  GPIO14&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GPIO15  
  GPIO18&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GPIO19  
  SCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SDA  
  GND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CHIP_PU    
