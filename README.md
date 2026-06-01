# Robotic-Hand
Designed and built a robotic hand that mimics hand movements through a CV and hand tracking library.

hand_landmarker.task - The AI model that knows how to detect a hand. I had this in the same code folder with the python script.


robot_hand.ino - The code for the Arduino Uno microcontroller. Mostly handles actuation and deleting messages in the buffer.


robot_hand.py - Python script for detecting hand movements. Impelements vector subtraction and dot product formula for finding the bend angle
of each finger.


robotic_hand.png - Circuit schematic for the robotic hand.
