# Measuring Distance
Measuring Distance Using Raspberry Pi, breadboard, LED, Buzzer and ultrasonic sensor
An interface made of an LED, a Buzzer, and an ultrasonic sensor is a perfect match for measuring the distance to an object using ultrasonic waves. The step-by-step illustration shows the process of creating a distance-measuring tool using a Raspberry Pi and a breadboard. The measuring tool consists of a LED light, a buzzer, and an ultrasonic sensor. The ultrasonic sensor sends sound wave frequencies, while the buzzer produces sound when it detects an object.
To create this device, you will need the following:
•	Raspberry Pi
•	Breadboard
•	Four jumper cables
•	LED light of any color
•	Ultrasonic sensor
•	buzzer 
The diagram below shows a schematic illustration of how I set up the device using the components mentioned, Raspberry Pi and a breadboard.
![rasp1](https://github.com/jbrant0/Final-Project-IOT/blob/4b59f0770641846ae50a45a681965bce5fb63f57/IMGREF.png)

Step 1
I began by mounding the ultrasonic sensor on the breadboard, as shown below.
![rasp2](https://github.com/jbrant0/Final-Project-IOT/blob/7f87930e4643233e72f167dc43a17a09072aabb5/IMG1.png)

Step 2
Then I connected the LED light as shown.

![rasp3](https://github.com/jbrant0/Final-Project-IOT/blob/7f87930e4643233e72f167dc43a17a09072aabb5/IMG3.png)

Step 3
Then I introduced the buzzer, as shown in the diagram.


![rasp4](https://github.com/jbrant0/Final-Project-IOT/blob/7f87930e4643233e72f167dc43a17a09072aabb5/IMG4.png)

Step 4

Caution:
To avoid damage to the Raspberry Pi;
•	Turn off the Raspberry Pi when connecting GPIO ports with the cables.
•	Use resistors
•	Avoid bending GPIO ports
Follow the following illustrations,
	Connect the negative sides of the buzzer and the LED using a jumper wire
	Put a resistor to the positive side of the LED
	Add a resistor for the echo pin of the ultrasonic sensor
	Put a jumper wire for the ultrasonic sensor echo, then put it to the Raspberry Pi GPIO number 23
	Connect a jumper wire to the ultrasonic sensor trigger pin and the Raspberry Pi GPIO port number 24
	Connect the voltage pin of the ultrasonic sensor to the raspberry pi voltage 5 pin. 
	Connect the Buzzer to GPIO pin number 25
	Connect the LED to pin number 18
	Using a jumper wire, connect the ground of the LED and the buzzer to the Raspberry Pi Ground.
The setup should resemble the figure below.


![rasp5](https://github.com/jbrant0/Final-Project-IOT/blob/main/IMG5.png)


Step 5
The subsequent step is an illustration of writing the code that simulates the functionality of the device measuring distance using the Raspberry Pi, Buzzer, and ultrasonic sensor. The code used for this simulation is found at (https://github.com/jbrant0/Final-Project-IOT/blob/bb8310c90197da48bbad9f62982d25a69c38e23d/Main%20Code). The executable program is created from a pycharm IDE. Create a new project named MeasuringDistanceUsingRaspberry.py, then copy and paste the code (https://github.com/jbrant0/Final-Project-IOT/blob/bb8310c90197da48bbad9f62982d25a69c38e23d/Main%20Code). And save, then run. The pycharm IDE should be installed in Raspberry Pi. 

![rasp6](https://github.com/jbrant0/Final-Project-IOT/blob/4b59f0770641846ae50a45a681965bce5fb63f57/CODE1.png)

![rasp7](https://github.com/jbrant0/Final-Project-IOT/blob/main/CODE2.png)

![rasp8](https://github.com/jbrant0/Final-Project-IOT/blob/main/CODE4.png)

Step 6
After writing the code, you can now execute the program by hitting the run button. The distance of the object will be varied. 


![rasp9](https://github.com/jbrant0/Final-Project-IOT/blob/b6d406835956f6d372e12179455e28a55e228cdb/FINAL.png)

Conclusion
The tool used to measure objects' distance would be available after following the above steps. The video link provides guides on how the device will work after completely assembling the components. 
