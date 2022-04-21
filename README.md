# M2_SmartLocationPointer
INTRODUCTION:
1.1	Project Scope: The evolution of workplaces and homes over a past few years has been enormous. The smart building of all sorts of shelters has worked to get the most out of that space. Deployment of IoT algorithms and machine learning in smart building to increase work efficiency, predictive maintenance, save the environment and minimize energy waste, track activities and build health and safety against environmental changes have expanded boundaries of the emerging technology. Our model can be used by architects and engineers while working on sites to measure the humidity, temperature, CO2 and light intensity to predict the suitability of locating a particular section of the building or a house at the piece of land. This escalates the scope of smart construction and let us consider major but highly ignored factors while constructing a new place.
1.2 We have used the two top-most burning technologies in current era i.e. Internet of Things (IOT) and Machine Learning (ML/AI). The idea of the project is as follows: Collecting the data using various IOT-sensors, further analysing it using Python, drawing some very important insights from the data, training a machine learning model on the very same data. We also have evaluated the trained model to generalize pretty well on the unseen instances and thus avoiding the problem of Overfitting and Underfitting of Models. The trained model is then deployed at the backend of the mobile phone application, where the data will be given by the user and the machine learning model would predict something which would be displayed in the prediction page.
![image](https://user-images.githubusercontent.com/101264490/164463274-242d4b40-5bf7-45b5-9122-07e90289c53f.png) FIG1.0

1.3	We have simply visited 5 rooms and collected data using DHT11 sensor which gives us the temperature and humidity readings for that room, Ambient Light Sensor which gives us the intensity of light in that room in lux (unit for measuring light) and MQ-135 sensor which computes the co2 concentration in the room. Thus, we visited each of the 5 rooms and collected data using all of the sensors above mentioned and after collecting the whole of data, it looks like as described in Figure 1.0.

Project Objective:  The objective of building a “Smart Location Pointer” is to contribute in the designing of homes, offices, restaurants and all other accommodations and workplaces differently according to their unique needs. Hence, we have created a mobile application where the user needs to enter the data of each of the feature i.e. co2, humidity, light, temperature and based upon these values, the model would suggest which room it should be. Hence, we have deployed the machine learning model trained using Softmax Regression which does multi-class classification and based upon the values obtained by each of the IOT-sensor, it would suggest the best possible room it should be. Now, the data on which we have Our model is trained using a set of data of five rooms. The application can be used at construction sites or prospective places for construction to predict the suitability of locating a particular room like washroom, bedroom, conference room etc.

BLOCK DIAGRAM:
The block diagram clearly shows how the whole project has been implemented and what steps have been performed to completely and successfully achieve the desired project:
![image](https://user-images.githubusercontent.com/101264490/164463503-3ca7a39f-e578-4c87-8c48-cf4092150c93.png) FIG1.1

PROJECT PLANNING 
Project Cost Estimation: 1800/-
Project Execution:

COMPONENTS USED:
A.	Arduino UNO
Arduino Uno is a microcontroller board based on the ATmega328P (datasheet). It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analogue inputs, a 16 MHz ceramic resonator (CSTCE16M0V53-R0), a USB connection, a power jack, an ICSP header and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started.
"Uno" means one in Italian and was chosen to mark the release of Arduino Software (IDE) 1.0. The Uno board and version 1.0 of Arduino Software (IDE) were the reference versions of Arduino, now evolved to newer releases. The Uno board is the first in a series of USB Arduino boards, and the reference model for the Arduino platform; for an extensive list of current, past or outdated boards see the Arduino index of boards.
B.	Temperature Sensor:
A temperature sensor is an electronic device that measures the temperature of its environment and converts the input data into electronic data to record, monitor, or signal temperature changes. There are many different types of temperature sensors. Some temperature sensors require direct contact with the physical object that is being monitored (contact temperature sensors), while others indirectly measure the temperature of an object (non-contact temperature sensors). We have used DHT11 sensor to record the temperature and humidity values from the environment in Fahrenheit.

C.	CO2   Gas Sensor:
A carbon dioxide sensor or CO2 sensor is an instrument for the measurement of carbon dioxide gas. ... Measuring carbon dioxide is important in monitoring indoor air quality, the function of the lungs in the form of a capnograph device, and many industrial processes. We have used MQ-135 sensor for recording the concentration of CO2 in parts-per-million.

D.	Humidity Sensor:
A humidity sensor is an electronic device that measures the humidity in its environment and converts its findings into a corresponding electrical signal. ... Relative humidity is calculated by comparing the live humidity reading at a given temperature to the maximum amount of humidity for air at the same temperature. As discussed above, we have used DHT11 sensor for recording humidity concentration in the environment in gram-per-meter-cube. 

E.	Light Intensity Sensor:
Light Sensors. The light sensor is a passive device that converts the light energy into an electrical signal output. ... Phototransistors, photoresistors, and photodiodes are some of the more common type of light intensity sensors. Photoelectric sensors use a beam of light to detect the presence or absence of an object. We have used ambient light sensor for recording the intensity of light in the environment in lux.

EXECUTION AND IMPLEMENTATION DETAILS:
![image](https://user-images.githubusercontent.com/101264490/164465979-f9e28b7f-eadf-4d63-b3ed-54f5c4f70f38.png) FIG.1.2




