# Two-mode-robot-Arduino
Robot's 2 states:
1. Autonomous.
2. Semi-autonomous.

Autonomous mode - a distance sensor will be installed on the robot on a servo motor. Plus two IR sensors and a color sensor.
The robot will follow a black rail and stop at obstacles. When there is an obstacle in front of the robot it will stop in its place and wait until the obstacle is removed.
In addition, the robot will detect colors. The robot will turn on the LED lights
depending on the color received by the color sensor located below it. The component used to turn on the light - a strip
RGB LEDs.

Semi-autonomous mode - This mode is called semi-autonomous because the robot is also controlled by an external user.
A Bluetooth communication component will be placed on top of the robot. Using the Bluetooth, the robot is connected to a smartphone.
Using the smartphone we control the travel directions of the robot. The control of the robot will be done
using commands from an app installed on a smartphone (Here's a link for installation: https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller).

Requirements:
The project will contain the following components:
1. Arduino 
2. IR sensors 
3. DC motors + current drivers
4. Servo motors
5. Distance sensor (ultra-sonic SRF05)
6. Color sensor (TAOS -TCS34725)
7. RGB LED strip + current driver (ULN2803) for LEDs that consume above 5v.
8. Bluetooth component (HC-05 and 9600 bauds)
9. Potentiometer



