```java
// RGB Solution - uses a particular kind of RGB LED (yours may be the opposite)

int redPin = 11;
int greenPin = 10;
int bluePin = 6;

void setup() {
  // put your setup code here, to run once:
  pinMode(redPin,OUTPUT);
  pinMode(greenPin,OUTPUT);  
  pinMode(bluePin,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  setColor(255,0,0);
  delay(2000);
  setColor(0,255,0);
  delay(3000);
  setColor(190,120,0);
  delay(2000);
}

// Depending on the style of RGB LED you have, you may need to use this function
void setColor(int red, int green, int blue)
{

  red = 255 - red;
  green = 255 - green;
  blue = 255 - blue;
  analogWrite(redPin, red);
  analogWrite(greenPin, green);
  analogWrite(bluePin, blue);  
}
```
