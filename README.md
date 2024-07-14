Arduino for blinking 4 led red light 

The blinking of 4 LEDs with Arduino is a simple and educational project that will show a beginner how to use an Arduino board to control a few LEDs. 
By writing a basic program, you could make the LEDs blink in a sequence, therefore showing the way to control digital outputs on an Arduino. 
It's a good project for getting to know basic electronics, programming, and how Arduino boards function in an interactive and hands-on manner. 
Get your Arduino board and some LEDs to start creating your own blinking light show!

write Arduino code for blinking 4 led red light 

cpp
#define LED1 2
#define LED2 3
#define LED3 4
#define LED4 5

void setup() {
  pinMode(LED1, OUTPUT);
  pinMode(LED2, OUTPUT);
  pinMode(LED3, OUTPUT);
  pinMode(LED4, OUTPUT);
}

void loop() {
  digitalWrite(LED1, HIGH);
  digitalWrite(LED2, HIGH);
  digitalWrite(LED3, HIGH);
  digitalWrite(LED4, HIGH);
  delay(1000);
  
  digitalWrite(LED1, LOW);
  digitalWrite(LED2, LOW);
  digitalWrite(LED3, LOW);
  digitalWrite(LED4, LOW);
  delay(1000);
}
```
