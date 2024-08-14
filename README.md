# Arduino-Led-Blinking

This project shows how control the brightness of a red LED using an Arduino Uno board.

## Components:
#### Arduino Uno Board
#### Breadboard
#### Red LED
#### Resistor
#### Wires


## Code:

```
int ledPin = 13; // Define the pin where the LED is connected

void setup() {
  pinMode(ledPin, OUTPUT); // Initialize the LED pin as an output
}

void loop() {
  digitalWrite(ledPin, HIGH); // Turn the LED on
  delay(1000); // Wait for one second
  digitalWrite(ledPin, LOW); // Turn the LED off
  delay(1000); // Wait for one second
}
```

## Circuit:
![image alt]()

https://www.tinkercad.com/things/gE2IVvx2yv1-fantabulous-turing-jofo
