```java
#include <Servo.h>

Servo myservo;  // create servo object to control a servo

void setup() {
  myservo.attach(9);  // attaches the servo on pin 9 to the servo object
}

void loop() {
  myservo.write(180); // tell the servo motor to move to position 180 deg.
  delay(1000);        // wait 1 second
  myservo.write(45);   // tell servo motor to move to position 45 deg.
  delay(1000);        // wait 1 sec
}
```
