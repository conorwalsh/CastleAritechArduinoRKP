CastleAritechArduinoRKP
=======================

An Aritech Alarm compatible Remote Keypad that makes Alarm functions
accessible via any desktop or modern mobile phone browser.

![animation demo](https://github.com/OzmoOzmo/CastleAritechArduinoRKP/blob/d3811089084ef876fd581825e4229804a5692861/HowTo/ArduinoAritechInternetKeypadLoop.gif?raw=true)

Allows you to remote arm/disarm the panel as well as view logs etc.
Also Emails you when an Alarm happens.

Connection to the Panel requires either only a two or a four wire connection (your choice).


To compile, place all in a folder called "CastleAritechArduinoRKP"
and open the "CastleAritechArduinoRKP.ino" in Arduino IDE.

No libraries are required.


The circuit required is in the HowTo Notes Folder.

Ive put a step by step guide on Instructables [here (Link..)](http://www.instructables.com/id/House-Alarm-Internet-Dialer-With-Arduino-Reverse-E/).

April 2015

Changelog
=======================

New Circuit Diagram:

<img src="https://raw.githubusercontent.com/conorwalsh/CastleAritechArduinoRKP/master/HowTo/breadboard%20alarm%20serial%20annotations.png" width="350"/>

Changed ports to 80 (need to change line 64 in WebSocket.cpp aswell as config file).

Added warning email for things like power and battery failure.

January 2018


