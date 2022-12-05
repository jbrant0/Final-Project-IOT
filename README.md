# Measuring-Distance-Using-Raspberry-Pi
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
![rasp1](https://user-images.githubusercontent.com/56275470/205504578-576cc584-f368-4f46-9a92-51b04ffe4ccc.png)

Step 1
I began by mounding the ultrasonic sensor on the breadboard, as shown below.
![rasp2](https://user-images.githubusercontent.com/56275470/205504655-9627c360-943a-4282-a5cc-b7c874acc5b9.png)

Step 2
Then I connected the LED light as shown.

![rasp3](https://user-images.githubusercontent.com/56275470/205504910-764081cb-7b1f-478c-a3e1-de783de258fb.png)

Step 3
Then I introduced the buzzer, as shown in the diagram.


![rasp4](https://user-images.githubusercontent.com/56275470/205504945-2893d52a-71a8-4cd7-824e-756e65a6f4a1.png)

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


![rasp5](https://user-images.githubusercontent.com/56275470/205504967-fe17b974-c7c5-456e-9a50-9d74c31128cb.png)


Step 5
The subsequent step is an illustration of writing the code that simulates the functionality of the device measuring distance using the Raspberry Pi, Buzzer, and ultrasonic sensor. The code used for this simulation is found at (https://github.com/dgermillarcom/Measuring-Distance-Using-Raspberry-Pi/blob/main/MeasuringDistanceUsingRaspberry.py). The executable program is created from a pycharm IDE. Create a new project named MeasuringDistanceUsingRaspberry.py, then copy and paste the code (https://github.com/dgermillarcom/Measuring-Distance-Using-Raspberry-Pi/blob/main/MeasuringDistanceUsingRaspberry.py). And save, then run. The pycharm IDE should be installed in Raspberry Pi. 

![rasp6](https://user-images.githubusercontent.com/56275470/205505098-045a4f19-f1c7-42c7-8309-228885fd1113.png)

![rasp7](https://user-images.githubusercontent.com/56275470/205505105-14cfada5-a8ed-45b1-8bbd-7a5ef9a15a34.png)

![rasp8](https://user-images.githubusercontent.com/56275470/205505110-695b99d8-bc48-483f-9f67-22d23424aae9.png)

Step 6
After writing the code, you can now execute the program by hitting the run button. The distance of the object will be varied. 


![rasp9](https://user-images.githubusercontent.com/56275470/205505137-feba8f41-0c99-4a94-86dc-6956869b33f6.png)

Conclusion
The tool used to measure objects' distance would be available after following the above steps. The video link provides guides on how the device will work after completely assembling the components. 
