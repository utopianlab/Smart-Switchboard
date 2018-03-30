It's a Touch Smart Switchboard with Alexa control for home automation.

ESP32: The ESP32 microcontroller offers a lot of features that can be applied to a diverse set of applications. However we found it suitable for making a smart switchboard as we can use both the WiFi and Bluetooth in it for communicating to the cloud and at the same time communicating to other devices such as Motion sensor/Door Sensor.

The Proposed features are:
 
- A Touch Smart Switchboard for controlling all the Lights/fans

- An inbuilt Temperature sensor for monitoring the room temperature

- An inbuilt ambient light sensor for turning the lights on at dark hours.

- Using Alexa Voice control to control all the lights and fans.

https://youtu.be/7jChybAB1uc

The above video gives a short demo of the Smart switchboard with Alexa. Further Touch control will be added shortly

The code can be compiled by following the ESP-IDF framework method and can be executed in any of the ESP32 boards.

Although the hardware for the touch functionality and the battery powered motion/door sensor is ready. Software integrations are taking time and will be updated shortly.

Future Work to be done:

- A battery powered Motion/Door sensor to send data to ESP32 to control lights automatically.

- Dimming the lights/fans according to the sensor values

- An android app to control the lights/fans.

- Predictive models for personalizing the room for the user

- Energy analytics 
