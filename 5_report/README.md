# Abstract

The automated rain wiper system is used to detect rainfall and activate automobile automatic rain wiper without driver interaction. The system is developed to mitigate driving distractions and allow drivers to focus on their primary task of driving. The distraction eliminated with the development of this product is the manual adjustment of windshield wipers when driving in precipitation. The few seconds that a driver takes their attention off the road to adjust a knob while driving in poor weather conditions could potentially lead to car accidents.The system uses a combination of impedance and rain sensor to detect rain and its intensity. The system contains a controller that takes in the input signals from the sensors and controls the operation of the windshield wipers based on those input signals


# Introduction

A windscreen wiper is a device used to remove rain and debris from a windscreen. Almost all motor vehicles are equipped with such wipers, which are usually an essential requirement. A wiper generally consists of an arm, pivoting at one end and with a long rubber blade attached to the other. The blade is swung back and forth over the glass, pushing water from its surface. The speed is normally adjustable, with several continuous speeds and often one or more "intermittent"settings. Most automobilesuse two synchronized radial type arms. It takes a lot of force to accelerate the wiper blades back and forth across the windshield so quickly.


# Objective
The distraction considered in this project is the adjustment of wiper speed based on the intensity of precipitation falling. Sometimes dust particles floating in the air are covered in the windscreen during moving vehicle which could be another cause of accident. The manual adjustment of the wiper and windscreen washing spray distracts driver's attention, which may be a direct cause of accident. This project is up to minimize the drivers work by setting up automatic control system for windshield mountings which are wiper, and rain sensor. With drivers exposed to an ever increasing number of accidents, automatic rain-sensing wiper system, dust cleaning system and automatic sun visor system could be an even more appealing feature, as they work to minimize the time the driver must take his/her hands off the wheel. By using rain sensing device the wiper can be automated and light sensor can be useful to regulate the sun visor without even touching it. The pivotal concern is to render more attention of the driver on the road. The automated rain wiper system is used to detect rainfall and activate automobile automatic rain wiper without driver interaction. The system was developed to mitigate driving distractions and allow drivers to focus on their primary task of driving. The distraction eliminated with the development of this product is the manual adjustment of windshield wipers when driving in precipitation. The few seconds that a driver takes their attention off the road to adjust a knob while driving in poor weather conditions could potentially lead to car accidents.

The system uses a combination of impedance and Impedance sensor to detect rain and its intensity. The system contains a controller that takes in the input signals from the sensors and controls the operation of the windshield wipers based on those input signals [3].Nowadays, a new type of wiper system is starting to appear on cars that actually do a good job of detecting the amount of water on the windshield and controlling the wipers. The system uses a sensor that uses optical sensors to detect the moisture. The sensor is mounted in contact with the inside of the windshield, near the rearview mirror.The sensor works by projecting infrared light into the windshield at a 45-degree angle. If the glass is dry, most of this light is reflected back into the sensor by the front of the windshield. If water droplets are on the glass, they reflect the light in different directions. The wetter the glass, the less light makes it back into the sensor.



# Advantages
You can make your own.

Work with a basic principle.

Very easy to make.

Easy to handle.



# Disadvantages
Alert will be start when rain is there, sometimes it disturbs human.

It has to be in few heights so that something could not enter

# Block diagram of Wiper control system

![design 2](https://user-images.githubusercontent.com/101311812/168439417-85bd0c90-2096-4c27-af65-adaed8b020e3.jpeg)


# Automatic rain sensing car wiper

![design 3](https://user-images.githubusercontent.com/101311812/168439471-87c2fe25-2102-48d2-9cb4-3dd2ef137106.jpeg)


![design 4](https://user-images.githubusercontent.com/101311812/168439510-63a74f57-a1a7-47c5-a4f6-8138aeb645a8.jpeg)


# Test cases


# High Level Test Cases

| Test ID |	Description |	Exp.i/p |	Exp.o/p |	Actual o/p |	STATUS |
| --------| :-----------| :-------| :-------| :----------| :-------|
| 1 |	check if the BUTTTON is pressed |	program execution |	Microcontroller/Engine starts |	LED ON(RED)	    | PASS |
| 2 |	check if the BUTTTON is pressed |	program execution |	WIPER starts                  |	LED ON(BLUE)	  | PASS |
| 3 |	check if the BUTTTON is pressed |	program execution |	WIPER starts                  |	LED ON(GREEN)   |	PASS | 
| 4 |	check if the BUTTTON is pressed |	program execution	| WIPER starts	                | LED ON(ORANGE)  |	PASS |
| 5 |	check if the BUTTTON is pressed |	     -            | Microcontroller/Engine stops  | LED TURNED OFF  |	PASS |


# Low Level Test Cases

|Test ID |	Description |	Exp.i/p |	Exp.o/p |	Actual o/p |	STATUS |
| -------| :------------| :-------| :-------| :----------| :-------|
| 1 |	check if the BUTTTON is pressed       |	program execution  |	Microcontroller/Engine starts	               |  LED ON(RED)    |	PASS |
| 2 |	check if the BUTTTON is pressed again | program execution  |	WIPER starts and speed of wiper is slow	     |  LED ON(BLUE)	 |  PASS |
| 3 |	check if the BUTTTON is pressed again	| program execution  |	WIPER starts and speed of wiper is moderate  |	LED ON(GREEN)  |	PASS |
| 4 |	check if the BUTTTON is pressed again |	program execution  |	WIPER starts and speed of wiper is good      |	LED ON(ORANGE) |	PASS |
| 5 |	check if the BUTTTON is pressed again	|   -	               |Microcontroller/Engine stops	                 |  LED TURNED OFF  | PASS |


# Swot Analysis

![image](https://user-images.githubusercontent.com/101239044/168435202-68122941-ebd5-4d7c-a55a-cea1913f4c58.png)


# Output

![design 1](https://user-images.githubusercontent.com/101311812/168440064-0862db9f-1bff-4725-9bb9-b5867d718c17.jpeg)


![design 5](https://user-images.githubusercontent.com/101311812/168440078-653a194a-1c83-4353-9483-14a66f1b1cb2.jpeg)





