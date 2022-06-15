# RP-Pico-Door-Keyboard-Input
With this python project you can set up a Raspberry Pi Pico to send a keyboard input to your PC. Uses HID, works on any PC without installation

Can be used to close tabs or windows on your PC, when a door is opened. Uses a Raspberry Pi Pico and an HC-SR04 ultrasonic sensor. It communicates with the PC using Circuitpython and the HID Library, so it works on any computer without configuration.

The python code examples for the Raspberry Pi Pico are under ------. You can use them without editing, but i would recommend you to change the distance for the ultrasonic sensor and the position you have your webbrowser pinned to(uses WIN + 0-9 to change window).
The programs under ----- are used to create your own keyboard shortcuts and to spefify the distance to the door.