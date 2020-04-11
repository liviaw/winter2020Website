```java
/////////////////////////////////////////
// Push Button Demonstration ////////////
/////////////////////////////////////////

// ======================================
// Global variables
// ======================================
int pushPin = 7;
int ledPin = 13;

// --------------------------------------
// setup() method runs once, at the start
// of the sketch.
// --------------------------------------
void setup() {
  // Initialise pin modes
  pinMode(pushPin, INPUT);
  pinMode(ledPin, OUTPUT);
}

// -------------------------------------
// loop() method runs continuously
// -------------------------------------
void loop() {
  // Read value from pin assigned to
  // pushbutton
  int valRead = digitalRead(pushPin);
  // If button is not pushed down, 
  // turn light off.
  // Otherwise turn light on.
  if (valRead == LOW) {
      digitalWrite(ledPin, LOW);
  } else {
      digitalWrite(ledPin, HIGH);
  }

}
```
