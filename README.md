# Virtual-Environmental-Sensor-Simulation-using-ThingSpeak

Below are the steps which I followed in developing the IOT System:
1.	Create a Virtual Environment Station: I will write a python script to simulate  virtual sensor readings for 3 sensors- Temperature, Humidity and C02 sensor. The python code is written in the .ipynb file.
2.	Setup an MQTT Broker:
I will use ThingSpeak platform and add a MQTT Device as the broker to publish data.
3.	Publish Data to the MQTT Broker: The code in Step 1 includes the MQTT publishing logic using the paho-mqtt Python library.
4.	Create a Cloud-based Backend : 
•	Sign up for a ThingSpeak account.
•	Create a new channel for each type of data.
•	Note the channel IDs and write API keys.
5.	Display Data: use the built-in MATLAB visualization apps to display data.


Given below are the screenshots of the output of graphs which are developed with the code and visualizations:
![image](https://github.com/Mohit-Vadsak/Virtual-Environmental-Sensor-Simulation-using-ThingSpeak/assets/32741263/ec5f6392-5da4-446f-94ae-032a8ca1f173)
![image](https://github.com/Mohit-Vadsak/Virtual-Environmental-Sensor-Simulation-using-ThingSpeak/assets/32741263/eee4edc6-d187-484d-ad6c-a937eaec557e)
![image](https://github.com/Mohit-Vadsak/Virtual-Environmental-Sensor-Simulation-using-ThingSpeak/assets/32741263/77c57aa1-c865-4dcc-949b-493eaaa4b6bf)
![image](https://github.com/Mohit-Vadsak/Virtual-Environmental-Sensor-Simulation-using-ThingSpeak/assets/32741263/9630e051-953a-4e0e-943e-a56262df3f78)



