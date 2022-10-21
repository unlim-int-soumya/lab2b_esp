# ESE 519: Lab 2B Expansion Board Proposal

To test and blink the LED, I did the following procedures, as described in the lab handbook.

Finally, connect your RP2040 to the LED in the following manner:
1. I attached the Stemma QT breakout cable to the RP2040.
2. Then, Disconnect the breadboard's power supply.
3. Removed the jumper wire from the breadboard power line to the LED.

4. Replaced this connection with the wire from the preset GPIO data pin (NOT THE POWER PIN).

5. Connected the ground pin on the Stemma QT cable to the breadboard's ground pin.

6. Connected the GPIO data pin, NOT THE POWER. PIN, to the breadboard's power pin


The GIF of LED blinking is seen below.</Br>
![](https://github.com/satyajeetburla/Lab-2B-Proposal/blob/main/GIF/Blink.gif)</Br>
![](https://github.com/satyajeetburla/Lab-2B-Proposal/blob/main/GIF/UART.gif)</Br>


# Circuit Board Proposal

Firstly, We are planning to design an 7-segment display using LED. Then we want to use a brightness sensor (LDR sensor / APDS 9960) to detect brightness and display it using our custom designed 7-segment display in relative terms of 0 - 9.
For the next lab, I've opted to build a circuit utilizing an RP2040, a breadboard, an LDR sensor, a 7-Segment LED display, and Jumper Wires that will sense the brightness using the LDR sensor and then show a value ranging from 0 to 9 based on the brightness value.

Although my main goal is to sense the brightness of the room using LDR sensor and display a normalized value using LEDs creating a 7-segement display. After that I will move forward to display its value in a real 7-segment display.

The components that we will be using are shown below. 
![](https://github.com/satyajeetburla/Lab-2B-Proposal/blob/main/GIF/Breadboard%20(1).png)
# Required Components
1. 7 LEDs
2. 1 LDR Sensor or Brightness Sensor
3. 1 7-segment Display
4. 1 Breadboard
5. 1 RP2040
6. 1 Servo Motor
7. Few Jumper Wires

We already have a breadboard, an RP2040, and three LEDs from the aforementioned components. We intend to acquire additional components from Detkin Lab.

If time allows, we will also integrate certain functions that are entirely dependent on servo motor speed control via our brightness sensor. To try this thing out, We also need one extra componet; Servo Motor that we hope to get from the Detkin Lab.
