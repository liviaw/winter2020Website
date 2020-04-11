```java
// Solution for traffic lights activity

int red = 7;
int yellow = 6;
int green = 5;

void setup() {
  // initialize the pins as outputs
  pinMode(red, OUTPUT);
  pinMode(yellow, OUTPUT);  
  pinMode(green, OUTPUT);
}


void loop() {
  digitalWrite(red, HIGH);    // turn the red LED on    
  delay(2000);                // wait for 2 secs
  digitalWrite(red, LOW);     // turn the red LED off
  digitalWrite(green, HIGH);  // turn the green LED on
  delay(3000);                // wait for 3 secs
  digitalWrite(green, LOW);   // turn the green LED off
  digitalWrite(yellow, HIGH); // turn the yellow LED on
  delay(2000);                // wait for 2 secs
  digitalWrite(yellow, LOW);  // turn the yellow LED off
}
```
