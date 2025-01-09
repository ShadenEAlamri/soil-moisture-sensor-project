# soil-moisture-sensor-project
This project is designed to help you monitor soil moisture levels and automatically water your plants when needed. We’ll use various electronic components to set up a simple system that makes plant care easier!

## Components Used
1)Arduino Uno
What it is: A small computer board that we program to control everything.
How we use it: It reads data from the moisture sensor and decides when to turn on the water pump.

2)Soil Moisture Sensor
What it is: A device with two metal probes that measure how wet the soil is.
How we use it: Stick the probes in the soil to get readings that tell us how much moisture is present.

3)Breadboard
What it is: A tool where we can build our circuits without soldering.
How we use it: It holds all our electronic parts and connects them easily.

4)LEDs
What it is: Small lights that can light up to show different statuses.
How we use it: One LED will glow when the soil is dry, and the other when it’s adequately moist.

5)Resistors
What it is: Components that limit the flow of electricity.
How we use it: Resistors protect our LEDs from getting too much power.

6)LCD Display (16x2)
What it is: A screen that shows information in text form.
How we use it: It displays the current moisture level and whether the pump is on or off.

7)Water Pump
What it is: A small motor that moves water.
How we use it: When the soil is dry, the Arduino tells the pump to turn on and water the plants.

8)Servo Motor
What it is: A motor that can move to specific angles.
How we use it: It can control a valve for the water flow.

9)Jumper Wires
What it is: Wires that connect all our components.
How we use it: They link everything together on the breadboard and to the Arduino.

10)Power Supply
What it is: A source of electricity for our project.
How we use it: We can power the Arduino through USB or batteries.

## how to build and use it
Step 1: Gather all the component

Step 2: build the Circuit
1)Arduino:
Connect the Soil Moisture Sensor:
VCC to the 5V pin on Arduino.
GND to GND on Arduino.
A0 to the A0 pin on Arduino.
2)LEDs:
Connect the longer leg of one LED to digital pin 9 through a resistor, and the shorter leg to GND.
Connect another LED the same way to digital pin 10.
3)LCD Screen:
Use the specific wiring diagram for the LCD display (usually involves connecting several pins to the Arduino).
4)Water Pump:
Connect it to digital pin 8 through a relay if necessary to control it safely.
5)Power Supply:
Connect the Arduino to a power source (battery).

Step 3: Write the Code and run it

Step 4: Test It Out
Stick the soil moisture sensor probes into the soil of your plants.
Watch the LCD display for moisture level readings.
Take note of how the LEDs behave and if the water pump activates when the soil is dry.

