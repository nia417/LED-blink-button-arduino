# LED-blink-button-arduino
A beginner Arduino project using Tinkercad. Blinks an LED using pin 13. My very first electronics project!
I used [Tinkercad circuits] (https://www.tinkercad.com/) to simulate an Arduino Uno blinking an LED.

# What I learned
- How to find and use different learning sources
- What components are needed for creating a circuit
- How to wire an LED and resistor correctly
- What pin 13 on Arduino does
- How to use 'digitalWrite()' and 'delay()' in Arduino C
- How to write a description to demonstrate

# Circuit Description
- LED long leg -> resistor -> Pin 13
- LED short leg -> GND
- Arduino Uno used in Tinkercad
- ![My Tinkercad Circuit](https://github.com/nia417/LED-blink-button-arduino/blob/main/circuit.png?raw=true)

# Code Example
'''cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}

# How I feel
This tiny project helped me gain confidence as I begin my engineering degree!
