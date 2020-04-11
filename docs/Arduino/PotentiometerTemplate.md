```java
/////////////////////////////////////////
// Arduino Potentiometer Demonstration //
// UNSW CompClub 2020 Summer Workshop  //
/////////////////////////////////////////

// ======================================
// 'Pin' variables 
// ======================================

//TODO: fill in the pin numbers
int inputPin = ??
int ledPin = ??

// --------------------------------------
// setup() method runs once, at the start
// of the sketch.
// --------------------------------------

void setup() {
  // Initialise communications with the Serial
  Serial.begin(9600);
  // TODO: Initialise pin modes

}

// ------------------------------------
// loop() method runs repeatedly
// ------------------------------------
void loop() {
  // First, read in the value from the
  // pin we assigned to the potentiometer.
  // TODO:
  int value = analogRead(???);
  // Write an appropriate amount of voltage
  // to the LED.
  // Remember: analogRead values go 
  // from 0 - 1023, but analogWrite
  // goes from 0 - 255. 
  // How can you ensure you'll always be 
  // writing to a value between 0 and 255?
  //TODO: 
  analogWrite(???);
  Serial.println(value / 4);
  // Delay for 10 ms.
  delay(10);
}
```
