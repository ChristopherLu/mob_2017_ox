This is a demonstration of IOT with B-L475E-IOT01A2 and Amazon AWS
The demonstration includes two parts:
a) Getting information from thermometer
b) Controlling a LED light on the board

The structure of the project is as follows:
IOT device is connected to AWS server with Wifi. There is a MQTT broker on the server and the IOT device will conmmunicate with the server through MQTT protocol.
A python client running on the Ubuntu virtual machine is also connected to the AWS server, and will use MQTT protocol to conmmunicate.

Steps to connect your IOT device to AWS:
a) use 5V power source to supply power to the board.
b) press the black button (RESET) on the board
c) wait about 15s to let the board initialize and connect to AWS

You can toggle the button with the blue button on the board.
