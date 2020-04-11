```java
// Solution for blink activity
void setup() {
  // initialize digital pin 7 to be output
  pinMode(7, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
    digitalWrite(7, HIGH);  // turn the LED on           
    delay(1000);              // wait for a second           
    digitalWrite(7, LOW);   // turn the LED off           
    delay(1000);              // wait for a second
}
```
