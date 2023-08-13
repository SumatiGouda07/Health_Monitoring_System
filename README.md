# Health_Monitoring_System

The project is all about ESP32 based Patient Health Monitoring System which will monitor the parameters like Room Temperature, Room Humidity, Heart Rate, Oxygen Saturation (Sp02) in blood, and body temperature of patients on the ESP32 Webserver.

### Introduction
Healthcare is given extreme importance now a-days by each country with the advent of the novel corona virus. So, in this aspect, a health monitoring system is the best solution for such an epidemic.Health care technology is rapidly being revolutionized with the help of the Internet of Things (IoT). Monitoring the health status of a covid patient is a hard task because of our busy schedule and our daily work.  This device uses an ESP32 web server to track patient health using this monitoring system. Hence, patient health parameters such as body temperature, heart rate (BPM), blood oxygen levels (Sp02) as well as room temperature and humidity can be monitored from any device (like Smartphone, PC, Laptop, Smart TV,.) That support browsing capabilities.



### METHODOLOGY

#### Components Required
  * ESP32 Board
  * MAX30100 Pulse Oximeter
  * DS18B20 Temperature Sensor
  * DHT11 Sensor
  * 4.7K Resistor

#### Components Descriptions

  * #### ESP32
    ESP32 is a low-cost, low-power system on a chip (SoC) series with Wi-Fi & dual-mode Bluetooth capabilities.ESP32 is highly integrated with built-in antenna switches, RF 
    balun, power amplifier, low-noise receive amplifier, filters, and power management modules. Engineered for mobile devices, wearable electronics, and IoT applications, 
    ESP32 achieves ultra-low power consumption through power saving features including fine resolution clock gating, multiple power modes, and dynamic power scaling.
  * #### Max30100
    The MAX30100 is an integrated pulse oximeter and heart rate monitor sensor solution. It combines two LEDs, a photodetector, optimized optics, and low-noise analog signal 
    processing to detect pulse oximetry and heart-rate signals. The MAX30100 operates from 1.8V and 3.3V powersupplies and can be powered down through software with negligible 
    standby current, permitting the power supply to remain connected at all times.
  * #### DHT11
    The DHT11 is a commonly used Temperature and humidity sensor. The sensor comes with a dedicated NTC to measure temperature and an 8-bit micro controller to output the       
    values oftemperature and humidity as serial data. The sensor is also factory calibrated and hence easy interface with other micro controllers. The sensor can 
    measure temperature from 0°C to 50°C and humidity from 20% to 90% with an accuracy of ±1°C and ±1%. So if you are looking to measure in this range then this 
    sensor might be the right choice for you. 
  * #### DS18B20
    DS18B20 is a 1-Wire digital temperature sensor from Maxim IC. Reports degrees in Celsius with 9 to 12-bit precision, from -55 to 125 (+/-0.5). Each sensor has a unique 64 
    Bit Serial number etched into it - allows for a huge number of sensors to be used on one data bus. Power supply range is 3.0V to 5.5V Measures temperatures from –55°C to 
    +125°C (–67°F to +257°F)±0.5°C accuracy from –10°C to +85°C .

#### WORKING
To measure Heart Rate/Pulse (BPM) and Blood Oxygen Level (SpO2), we use the MAX30100 pulse oximeter sensor. Similarly, to measure body temperature, we use the DS18B20 temperature sensor. Meanwhile, the patient is inside the room. So we need monitor room temperature and humidity level as well. We should keep them in a room with a certain temperature and humidity level to not feel uncomfortable. Hence, we use the DHT22 Temperature & Humidity sensor.The reset button of ESP32. 

Once the code is uploaded to your ESP32 development board, you can open the serial monitor to see the program into action. The ESP32 will connect to your Wi-Fi Network. Once connected, it will display the ESP32 IP Address.Copy the ESP32 IP Address and paste it on your Web Browser. It will display the room temperature, room humidity, Heart Rate, Blood Oxygen Level, and body temperature, etc.


#### CONCLUSION
It empowers individuals to take control of their health by providing instant access to vital sign data and environmental conditions. By leveraging IoT technology, this system has the potential to revolutionize personal healthcare management and enhance overall well-being.Internet of things technology is in its starting face but it has potential to impact human healthcare and associated markets at a massive scale. Due to high-speed internet access and advanced sensor technology, it is possible to track human and other objects. Researchers have started to discover many technological solutions to improve the healthcare system.





    
