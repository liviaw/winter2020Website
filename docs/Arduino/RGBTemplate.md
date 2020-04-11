```java
// TODO: Choose appropriate pins for each colour
int redPin = ??;
int greenPin = ??;
int bluePin = ??;

void setup() {
  // put your setup code here, to run once:
  pinMode(redPin,OUTPUT);
  pinMode(greenPin,OUTPUT);  
  pinMode(bluePin,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  setColor(???); // set a red colour
  delay(2000);
  setColor(???); // set a green colour
  delay(3000);
  setColor(???); //set a yellow colour
  delay(2000);
}


void setColor(int red, int green, int blue)
{
  // TODO write to each pin and hence set the overall colour of the LED
}
```
