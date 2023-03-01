# Driver-Drowsiness-Detector

##	Introduction
Driver exhaustion is a noteworthy factor in countless mishaps. Late measurements gauge that yearly 1,200 passings and 76,000 wounds can be credited to fatigue related crashes.
Driver drowsiness and fatigue is a major factor which results into numerous vehicle accidents. Developing and maintaining technologies which can efficiently detect or prevent drowsiness at the wheel and alert the driver before am mishap is a major challenge in the field of accident prevention systems. Because of the dangerous that drowsiness can cause on the roads some methods need to be developed for preventing counteracting its effects.
With the advent of modern technology and real time scanning systems using cameras we can prevent major mishaps on the road by alerting car driver who is feeling drowsy through a drowsiness detection system.
The point of this undertaking is to build up a prototype drowsiness detection system. The spotlight will be put on planning a framework that will precise ly monitor the open or shut condition of the driver's eyes continuously.
By monitoring the eyes, it is believed that the symptoms of driver fatigue can be detected early enough to avoid a car accident. Detection of fatigue involves the observation of eye movements and blink patterns in a sequence of images of a face.


1.  Problem Statement
Designing a prototype Drowsiness Detection System which will focus on continuously and accurately monitoring the state of the driver’s eyes in real time tocheck whether they are open or closed for more than a given period of time

2.  Objectives Of Our Project
Driver drowsiness detection is a car safety technology which spares the life of the driver by avoiding mishaps when the driver is getting languid.
•	The primary goal is to initially plan a framework to distinguish driver's sluggishness by persistently checking retina of the eye.
•	The framework works disregarding driver wearing displays and in different lighting conditions.
•	To caution the driver on the identification of laziness by utilizing ringer or alert.
•	Speed of the vehicle can be reduced.

•	Traffic management can be maintained by reducing the accidents.

                        Software Requirements
                        OpenCV, dlib and Python

3.  Working
Drivers face is monitored throughout using a video or web camera. In order to detect the drowsiness the first step is to detect the face using the set of framestaken by the camera. Then the location of the eyes is detected and retina of the eyeis continuously monitored. The captured image is sent to the processor for image processing. It converts the received image to digital signal using Open CV.
The digital signal is transmitted from transmitter to the receiver. Both the transmitter and the receiver are paired up. The signal is then passed to the LPC2148, the microcontroller. If the signal crosses the threshold value of EAR for a given number of frames, then the alarm beeps and the speed of the vehicle is automatically reduced.

4.1.	Computational Analysis
   Dashboard mounted camera is used to monitor the eyes of the driver in real time to detect drowsiness

4.2.	Drowsiness Detection Design
   A camera is setup that looks for faces in the input video stream and monitors frames of faces. In the event that a face is identified, facial milestone identification is connected and the eye district is removed from the edges of the video stream.

6.	Summary:


  To get the outcome a large no of pictures were taken and their accuracy in deciding eye flickers and drowsiness was tried.

  For this venture we utilized a 5 megapixel webcam associated with the PC. The webcam had inbuilt white LEDs connected to it to show it is working. In real time scenario, infrared LEDs ought to be utilized rather than white LEDs with the goal that the framework is non- meddling. Inbuilt speaker is utilized to deliver sound output so as to awaken the driver when drowsiness is detected.

  The framework was tried for various individuals in various surrounding lighting conditions (daytime and evening time). At the point when the webcam backdrop illumination was turned ON and the face is kept at an ideal distance, at that point the framework can identify blinks and drowsiness with over 95% accuracy.

  This is a decent outcome and can be executed by real time systems as well. Sample outputs for various conditions in different pictures is given beneath. Three pictures were taken; one in which just the eyes were identified and the other in which they were not and another where drowsiness is detected.


##  Future Scope

This framework can be stretched out further to have abundant security highlights, for example,

just a certain no of individuals can have specialist get to or work the vehicle. If there should be an occurrence of an endeavor to robbery, the vehicle's motor don't begin or an alarm sounds.

A picture of the burglar is taken in an attempted theft &sent to the owner of the vehicle who can register a case against the thief of the vehicle.
