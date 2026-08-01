CareMate is an AI-powered home-assistant robot designed to support elderly people living
alone by improving safety, emotional wellbeing, and cognitive engagement. These are
common concerns related to elderly wellbeing. The robot is built using Raspberry Pi 4B
running Python on Linux, a Raspberry Pi Pico 2WH microcontroller running MicroPython,
multiple sensors, electronic components and AWS (Amazon web services) AI functionality.
CareMate provides nighttime safety support by detecting movement and turning on soft LED
path lighting to guide the person without bright lights.

It can also help remove small obstacles using its gripper. A Hall sensor detects if a door is left open, while a heat sensor checks for
dangerous appliance heat; CareMate then alerts the user using natural speech generated with AWS Polly.

For emotional support, the robot uses camera images and AWS Rekognition to detect sad
facial emotion, then wirelessly triggers family photos, videos, or music on the TV. CareMate
also runs a cognitive game using images, quizzes, speech input, and Amazon Lex V2 to
understand responses and talks back naturally
