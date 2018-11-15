# Arduino-Home-Security
A collection of circuits and devices that are being used to simulate a home security/comfort system

This was my main project for my grade 11 computer technolagy class where I succesfully recreated a mock home security/comfort system. How does it work? The user will first have to get into the system by completing a successful knock sequence. The user is given 3 tries before the system locks them out temporarly. If the user successfully completes the knock sequence, then they can accsess the system. The user is given the option between two modes; an automatic mode, and a manuel mode. For the automatic mode, all fuctions be automatically completed via the sensors. For example, if the temperature is below 18 degrees, then the heating motor will automatically turn on. If the temperature is over 25 degrees, then the air conditioning motor will automatically turn on. If the temperature is in between 18 and 25 then both motors will be turned off. Also in automatic mode, if the photoresistor detects a low lighting, then it will automatically turn on a blue light and using a motor, open the blinds. If it detects a high light, then it will shut off the light and close the blinds with the motor. For the manuel mode, these functions are left to the user. With the simple push of a push button, the user can decide if they want to air conditioning motor on/off, the heating motor on/off or neither. This extends to the lighting feauture as well. The user can decide if they want a bright lit room, or a dark room.

Components:
- Infra Red Reciever
- DC Motors
- Photoresistor
- Temperature Sensor
- 16X2 LCD
- Arduino
- Copper Wires
- Piezo Disk
- Push buttons
- LED's


Real Life Applications:
With this project, I have laid out the groundworks, or skeleton for an actual home comfort system along the lines of an Alexa. Given more time and more resources, I believe I could successfully create a real functioning home security/comfor system.


Design:
- Multiple circut boards, all connected with a central ground and power
- LCD screen giving the user information as they operate the system
- Easy interface, with buttons in practical locations near the LCD

Since video files are too large, I am linking my video demonstration to a seperate website. The link can be found below:
https://www.dropbox.com/s/wj7dqn8t0q6v35s/20180620_122929%20%281%29.mp4?dl=0
