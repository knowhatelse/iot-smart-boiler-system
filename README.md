# IOT - Smart boiler system
## Project description
"Smart boiler system" is a small IOT project that aims to enable the user to turn on or off the boiler in his house through a website and a microcontroller.<br>

The project itself is composed of three parts: the control part, the executive part and the connective part. <br>
When it comes to the control part, it is a web page through which the user has two possible options for turning on the water heater, namely:
  1. The first option is only turning on the water heater, which is preceded by setting the time for the automatic shutdown of the water heater. <br>
  2. Another option is to set the time when the water heater should turn on and then turn off independently. <br>
The executive part of the project is a simulation made in Tinkercad, which consists of an Arduino Uno R3 microcontroller as the main device that serves to connect other components, and also serves as the voltage for the components, then Keypad 4x4, which is responsible for simulating options from the control side (buttons number 1 represents the "Turn ON" option from the website, and button 2 represents the "Turn OFF" option from the website), 10 parallel connected 10mohm resistors to simulate a heater (there is no device in Tinkercad that can serve as a heater), and there is another 220ohm resistor that connects the resistors connected in parallel and the LED, which informs us whether the system is on or off.<br>

Due to the fact that the project was made as a simulation in Tinkercad, the Arduino itself cannot be connected to the page itself or to the database, therefore the connecting part is a second web page that communicates with the control page via Google Firebase, i.e. with the first web page page. The task of the second website is to show the user all the necessary information such as: whether the water heater is on and how much time is left until the water heater shuts down, or when the water heater is on and when it will be turned off. <br>
