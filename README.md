# Smart-Switchboard

It's a Touch Smart Switchboard with Alexa control for home automation.

ESP32: The ESP32 microcontroller offers a lot of features that can be applied to a diverse set of applications. However we found it suitable for making a smart switchboard as we can use both the WiFi and Bluetooth in it for communicating to the cloud and at the same time communicating to other devices such as Motion sensor/Door Sensor.

The Proposed features are:

 -A Touch Smart Switchboard for controlling all the Lights/fans
 
 -An inbuilt Temperature sensor for monitoring the room temperature
 
 -An inbuilt ambient light sensor for turning the lights on at dark hours.
 
 -A battery powered Motion/Door sensor to send data to ESP32 to control lights automatically.
 
 -Using Alexa Voice control to control all the lights and fans.
 
 ESP-IDF was used to program the ESP32. BME280 sensor was used to measure the temperature, pressure and humditity of the room. A custom made relay module was used to control electronic appliance.

Future Work planned:

- Dim all the lights and fan using the temperature and ambient light sensor

- Create an Android App to control the lights using mobile

- Optimize the touch sensor code for better operation

- Energy analytics for the user

- Use Predictive models for personalizing the home for the user
