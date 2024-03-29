# Connect-DHT11-Sensor-to-AWS-IOT
Using Esp8266 NodeMCU and DTH11 sensor send Temperature and Humidity to AWS IOT
Overview
This is a getting started tutorial about Amazon Web Services, i.e AWS IoT Core with ESP8266. The AWS IoT Core is a managed cloud service that lets connected devices easily and securely interact with cloud applications and other devices.

In this tutorial, we will learn how you can connect the ESP8266 with AWS IoT Core & publish sensor reading to AWS MQTT. For a demo, we will use the DHT11 Sensor and read the humidity temperature data. The NodeMCU ESP8266 will connect to the local WiFi network and will post the DHT11 Sensor data to AWS IoT Cloud. Not only posting data, but we can also receive the data from AWS Dashboard. Earlier, we learned how to post sensor data to AWS Dashboard using ESP32 & AWS IoT Core. But in the case of ESP8266 the process is little different.

The tutorial comprises multiple sections

Signing up & setting the Amazon Web Services
Installing Necessary Libraries to Arduino IDE & Writing an Arduino Sketch for the project
Creating a Thing is AWS
Creating Policy and attaching to Thing
Generating Certificates
Modifying Arduino Sketch according to Thing Data & Credentials
Subscribe & Publish Data to and from AWS Dashboard
This tutorial is for beginners who want to learn about the Amazon AWS IoT Core for IoT
![image](https://github.com/sushant1911/Connect-DHT11-Sensor-to-AWS-IOT/assets/25933685/eb919fcb-307c-47c1-8aca-3d3547b9ce96)
reference :https://how2electronics.com/connecting-esp8266-to-amazon-aws-iot-core-using-mqtt/    
refrence : https://www.youtube.com/watch?v=x9GfxgkEpXg
