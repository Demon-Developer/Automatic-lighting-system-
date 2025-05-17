Automatic Lighting System
This project is a simple automatic lighting system using an Arduino, ultrasonic sensor (HC-SR04), LDR (Light Dependent Resistor), and an LED. The system automatically turns the light (LED) on based on ambient light and distance to an object.

Features
Detects the presence of an object within 20 cm using an ultrasonic sensor.

Checks for low ambient light using an LDR.

Lights up an LED when it's dark or an object is detected nearby.

Components Used
Arduino board (Uno/Nano/etc.)

HC-SR04 Ultrasonic Sensor

LDR (Light Dependent Resistor)

10K Resistor (for LDR)

LED

Jumper wires

Breadboard

Circuit Connections
Component	Arduino Pin
HC-SR04 Trig	D2
HC-SR04 Echo	D3
LDR (via voltage divider)	Analog or Digital Pin (e.g., A0 or D4)
LED	D8

How It Works
The LDR checks if the ambient light level is low.

The ultrasonic sensor checks for an object within 20 cm.

If either condition is true, the LED will blink.

Otherwise, the LED remains off.

Usage
Upload the code to your Arduino.

Connect the components as per the circuit diagram.

Power the Arduino and observe the LED behavior.

License
This project is open-source and free to use for educational and personal use.
