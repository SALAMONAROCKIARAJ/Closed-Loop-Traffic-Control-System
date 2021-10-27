# Closed-Loop-Traffic-Control-System

Repository for 3 way closed loop traffic control system using Ultrasonic sensor

# About my work :
       Usually, the traffic system is open-loop but we can change it to a closed-loop and make our traffic system smart using an ultrasonic sensor.

# Why do we use an ultrasonic sensor, Why not cameras?
       Actually in some rural areas camera is not implemented and another reason is it is economical but for a more efficient way, we go for ML models to control traffic but I am not well versed in training ml models using image processing  so, I am made a closed-loop traffic control system with help of an ultrasonic sensor


# Working :

 Whenever the vehicle comes into the range of an ultrasonic sensor, According to the path, the loop opens  
For example: when a car is coming into the range of ultrasonic sensor in path 1, the path 1 will be opened .If 3 paths are full of vehicles, then each loop will be opened and closed with a short delay .As usual, if traffic is less, then in which path the vehicle is there, that path will be opened 
