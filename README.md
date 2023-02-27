# ultrasonic
Python app that measures water level of a coffee machine reservoir with an ultrasonic distance sensor, , and sounds an buzzer when the water level nears the top. 
The hardware consists of: Ultrasonic distance sensor and a raspberry pi pico on breadboard attached to coffee machine. The coffee machine has a water reservoir that is 9.5" deep. 
- Purpose of app is to constantly measure the level of the water in the coffee machine reservoir and when the water level fills to 2 inches from the top, sound a warning buzzer. 

~~~

PINs:

To wire the hardware to the breadboard, you'll need to connect the ultrasonic distance sensor and buzzer to the Raspberry Pi Pico as follows:

Connect the sensor's VCC pin to a 3.3V pin on the Pico
Connect the sensor's GND pin to a GND pin on the Pico
Connect the sensor's TRIG pin to GPIO pin 2 on the Pico
Connect the sensor's ECHO pin to GPIO pin 3 on the Pico
Connect the buzzer's positive (red) wire to GPIO pin 4 on the Pico
Connect the buzzer's negative (black) wire to a GND pin on the Pico
Note that you may need to adjust the GPIO pin numbers in the Python code if you wire the components to different pins on the Pico.
