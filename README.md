# IOT-PROJECT-RGB-MODULE-ACTIVATION-FROM-FIREBASE


## AIM

To create a firebase project with realtime database and to control RGB sensor module with data from firebase using ESP8266 interfaced with RGB sensor module.


## COMPONENTS

<br> 1.ESP8266 NodeMCU
<br> 2.RGB Sensor Module
<br> 3.Jumper Wire
<br> 4.USB cable


## CONNECTION

### RGB Sensor Module Pin Diagram
 
![rgb module](https://github.com/user-attachments/assets/b2759b29-a7b9-40f3-a4af-60a8f0493dec)

<br> - = Ground ----> GND
<br> B ----> D2
<br> G ----> D1
<br> R ----> D0


## PROCEDURE

<br> Step 1 : Interface ESP8266 microcontroller to Visual Studio Code using port.
<br> Step 2 : Interface ESP8266 microcontroller with RGB Sensor to blink red,green,blue light with delay.
<br> Step 3 : Install the Firebase-ESP-Client Library.Then, program the ESP8266 to Interface with Firebase.
<br> Step 4 : Need to insert your network credentials, URL database, and project API key for the project to work.


## OUTPUT

![IMG_1](https://github.com/user-attachments/assets/08810432-a0d0-4669-a7ca-a937e739051f)


## REFERENCE

<br> For Visual Studio Code, the libraries are,
<br> lib_deps =
<br> &ensp;&ensp;&ensp;&ensp;     mobizt/Firebase Arduino Client Library for ESP8266 and ESP32@^4.4.14
