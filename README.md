# Arduino Alarm Clock Controlled by Remote
![IMG-1111](https://github.com/JohnN310/Remote-Control-Alarm-Clock/assets/106787922/cb2b2420-a95a-4cc8-90a9-5ca9cb5c95b7)

## Project Overview
This Arduino-based project features an alarm clock with remote control capabilities. The system allows users to control various functions, including turning the display on and off, setting the clock, setting the alarm, and activating a buzzer when the alarm goes off. The project leverages Arduino hardware and Elegoo tools for seamless integration.

## Components Used
1. Arduino Board (e.g., Arduino Uno)
2. Elegoo Infrared (IR) Remote Control Kit
3. Real-Time Clock (RTC) Module
4. Buzzer
5. LEDs (for display)
6. Jumper wires
7. Breadboard

## Project Setup
1. Connect the RTC module to the Arduino board for accurate timekeeping.
2. Wire the LEDs to the Arduino to serve as the display.
3. Connect the buzzer to the Arduino for audio feedback during the alarm.
4. Set up the IR receiver module and wire it to the Arduino to enable remote control functionality.
## Arduino Code
The project's Arduino code is available in the 'alarm_clock_remote_control.ino' file. The code, written in C++, can be easily uploaded to your Arduino board using the Arduino IDE. Make sure to install the required libraries for the RTC module and IR remote control kit before uploading the code.

## Elegoo Tools
Elegoo tools, especially the IR remote control kit, play a crucial role in facilitating remote control functionality in the project. The kit provides a user-friendly solution for integrating infrared communication into Arduino projects.

## Remote Control Functions
1. Display Control:
Toggle the display on and off with the remote control.

2. Clock Setting:
Use the remote control to set the current time on the clock.

3. Alarm Setting:
Set the desired alarm time remotely.

4. Buzzer Activation:
Activate the buzzer remotely when the alarm goes off.

## How to Use
1. Upload the provided Arduino code to your Arduino board.
2. Connect all components following the project setup instructions.
3. ower on the Arduino board.
4. Use the Elegoo IR remote control to manage the display, set the clock, set the alarm, and control the buzzer.
   
## Notes
The project code is customizable, allowing users to add features or modify alarm settings.
Ensure the RTC module is correctly set to your local time.
Experiment with additional components and functionalities to enhance the project further.
Feel free to contribute to the project and share your enhancements with the community!

Author
Khoa (John) Nguyen
