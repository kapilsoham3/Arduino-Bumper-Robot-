# Arduino-Bumper-Robot-
In this project, I created a bumper robot using Arduino and the motor driver IC with a friend. We decided to make it so whenever the robot bumps, it moves backwards and goes to another direction. After bumping 10 times, it plays a tune. The robot is powered by an Arduino UNO and a 9V DC battery. 
# More about L293D
L293D is an integrated circuit with 4 ground values, 4 voltage pins and 4 input and output pins. The voltage pins involve 2 voltage pins for powering the IC, and 2 enabling pins that control the speed of the motor based on the amount of voltage provided. Each input and output pin controls each motor. In my bumper robot, there were 2 sets of 4  motors and by controlling the voltage that they got, we can control the direction of the motor. 
# How the Motors are connected
Each motor is mounted to the edge of the wooden board. Using Arduino, the motors either receive an output of HIGH or LOW. The two motors on the right will always have the same value and the 2 on the left. Now by controlling the 4 motors and Arduino, we can make our cars go back, left, right or forward. Since we are using a fixed DC voltage for our car, the speed will be fixed too. 
# Detecting Obstacles
Two bumper switches are soldered to the front of the board and connected to the Arduino to record input. When the car hits an obstacle, the buttons get clicked, giving an input of HIGH. After receiving the signal, it outputs the motors so that the car moves backwards and then turns to the right. There's a detector variable that's counting the number of obstacles we have hit.
# LED Lights
The car's direction signals different LED lights to turn on. If it's moving forward, it shows a green light, when moving backwards, it shows a red light and when turning, it shows a yellow light. 
# Special Gimmick
We decided to add a special gimmick to our car and decided to use a piezo electric buzzer to make a tune when the car runs into something 10 times. After hitting an object 10 times, the car stops and the car backs up, stops and plays Jojo's theme. While playing the theme, it shows a LED display using the red, yellow and green lights. After the tune, the car goes back to turning right and moving forward until it hits another obstacle. The counter is reset to 0.  
# Conclusion
Thank you for reading more about my Arduino Bumper Robot. It was a fun project that I really enjoyed working on. I have uploaded a video file that shows a demonstration of the Arduino Robot
