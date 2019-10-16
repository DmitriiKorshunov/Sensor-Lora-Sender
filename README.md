# Sensor-Lora-Sender


Project: Sensor-Lora-Sender-Receiver

This project is a part of the software of greenhouse.

You should download this list of library. There are some links on the GitHub:

1) https://github.com/adafruit/DHT-sensor-library
2) https://github.com/adafruit/Adafruit_Sensor
3) https://github.com/HelTecAutomation/Heltec_ESP32

"Sender" is the code for sending data to base module. 
"Receiver" is the code for receiving data.

 
-----------------------------------------------------------------------------------
26.06.2019
1-st generation

Sender module: Sender module dumps data from DHT11 and sends its to the base module.
Options: 1) Temperature 2) Humidity 

Receiver module: There is the code from example by https://github.com/HelTecAutomation/Heltec_ESP32.
It is called:  OLED_LoRa_Receiver.ino

------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------
03.07.2019
2-st generation

Sender module: Sender module dumps data from DHT11 and sends its to the base module.
Options: 1) Temperature 2) Humidity. 
Also, system can include some sender modules. You can choose id for every device. 


Receiver module: This is the code from example ( https://github.com/HelTecAutomation/Heltec_ESP32 ) with some modifications.
You can see it here: https://github.com/DmitriiKorshunov/TempReciever 

-----------------------------------------------------------------------------------
16.10.2019
3-rd generation 

Sender module has personal number. Please, write unificial number in variable "ND".
Source code has two speciafication for DHT or DS sensors.
This code as optimization as older versions.
