/*
  Project: LED Blinking using Arduino UNO
  File: LED_Blinking.ino
  Author: Om Mangate
  Description:
  This program turns an LED ON for one second and OFF for one second repeatedly.
  The LED is connected to digital pin 13 of the Arduino UNO board.
  The Serial Monitor displays messages indicating the LED status.
*/

int ledPin = 13;  // LED connected to digital pin 13

void setup() {
  // Set pin 13 as output
  pinMode(ledPin, OUTPUT);

  // Start serial communication for debugging
  Serial.begin(9600);
  Serial.println("LED Blinking Program Started...");
}

void loop() {
  // Turn the LED ON
  digitalWrite(ledPin, HIGH);
  Serial.println("LED ON");
  delay(1000);  // Wait for 1 second

  // Turn the LED OFF
  digitalWrite(ledPin, LOW);
  Serial.println("LED OFF");
  delay(1000);  // Wait for 1 second
}
