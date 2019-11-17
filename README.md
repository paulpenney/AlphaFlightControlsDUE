# AlphaFlightControlsDUE
Using Arduino DUE to solve Honeycomb Alpha Dead Zone and Resolution Problems

See the Youtube Guide Here: https://www.youtube.com/watch?v=Zw6lMA6qTBs&feature=youtu.be

## Firmware Flashing Guide

I'm going to try and explain this as well as I can for someone who has never used Arduino. First let me tell you that "Arduinos" are the physical circuit boards and chips, and the "Arduino IDE" is the software program we use to upload code to it. "Libraries" are programs that people create for the Arduino IDE. 

### Installing Arduino IDE Software

1) Download the Arduino IDE from here: https://www.arduino.cc/en/Main/Software
2) Install Arduino 
3) Click the "Clone or Download" green button at the top right of this page and download this repository.
4) Install the "Joystick" library by unzipping it's contents to "YOUR USER ACCOUNT\Documents\Arduino\libraries"

### Preparing To Flash

5) Plug your Arduino DUE board into your computer via the "Programming Port" (Nearest the power connector input - should be labeled on the back too)
6) Open up the "AlphaFlightControlsDUE.ino" file in the Ardino IDE. 
7) Go to tools > board > board manager. Search for "Arduino Due". Install the "Arduino SAM Boards" library.
8) Go to tools > board and select "Arduino Due (Programming Port)"
9) Go to tools > port and select the COM port for your Arduino Due. 
10) Go to sketch > upload. Try it a couple times if it doesn't upload sucessfully at first. Turn on 'verbose output' during compile and upload in file > preferences if you need to see more information.
11) Congrats! Return to the YouTube video to finish the installation. At this point you should be able to plug the Aruduino DUE into your computer through the Native USB port (the other port) and it should show up as a joystick.
