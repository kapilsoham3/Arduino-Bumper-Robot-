# Arduino-Bumper-Robot-
In this project, I created a bumper robot using Arduino and the motor driver IC with a friend. We decided to make it so whenever the robot bumps, it moves backwards and goes to another direction. After bumping 10 time, it plays a tune. The robot is powered by an Arduino UNO and a 9V DC battery. 
# More about L293D
L293D is an Integrated circuit with 4 ground values, 4 voltage pins and 4 input and output pins. The voltage pins involve 2 voltage pins for powering the IC, and 2 ebabling pins that control the speed of the motor based on the amount of voltage provided. Each input and output pin control each DC motor. In my bumper robot, there were 2 sets of 4 DC motor and by controling the voltage that they got, we can control the direction of the motor. 
# How the Motors are connected
Each motor is connected to the edge of a wooden board. Using arduino, they either recieve an output of HIGH or LOW. The two motors on the right will always have the same value and the 2 on the left will always have the same value. Now by controlling the 4 motors and Arduino, we can make our cars go back, left, right or forward. Since we are using a fixed DC voltage for our Car, the speed will be fixed too. 
# Detecting Obstacles
Two bumper switches are soldered to the front of the board and connected to the arduino to record input. When the car hits an obstacle, the buttons get clicked, giving an Input of HIGH. After recieving the signal, it outputs the motors so that the car moves backwards and then turns to the right. There's a detecter variable that's counding the number of obstacles we have hit. 
# LED Lights
The car's direction, signals different LED lights to turn on. If it's moving forward, it shows a green light, when moving backwards, it shows a Red light and when turning, it shows a yellow light. 
# Special Gimmick
We decided to add a special gimmick to our car and decided to use a piezo electric buzzer to make a tune when the car runs into something 10 times. After hitting an object 10 times, the car stops and the car backs up, stops and plays Jojo's theme while showing a LED display using the Red, Yellow and Green lights. After the tune, the car goes back to turning right and moving forward untill it hits another obstacle. The counter is reset to 0.  
# Conclusion
Thank you for reading more about my Arduino Bumper Robot. It was a fun project that I really enjoyed working on. I have uploaded a video file that shows a demonstration of the Arduino Robot
