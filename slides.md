layout: true
class: center, middle

---

# Arduino and Electronics

---

# Maybe you're wondering
* What is Arduino?
* Why Arduino?
* How Arduino?

---

# arduino.cc says:
> Arduino is an open-source electronics prototyping platform based on flexible, easy to use hardware and software.
> It's intended for artists, designers, hobbyists and anyone interested in creating interactive objects or environments.

---

# Open-Source
* All of the software is free and on Github
* Hardware schematics and EAGLE files are also free

![Eagle](http://articlefind.files.wordpress.com/2012/01/eagle-pcg.jpg)

---

background-image: url(http://arduino.cc/en/uploads/Main/ArduinoSeverinoSchematic.png)

---

# Buy
![Uno](http://arduino.cc/en/uploads/Main/ArduinoUno_R3_Front_450px.jpg)

~ $20

---

# Or DIY
![DIY_Arduino](https://mecharobotics.files.wordpress.com/2012/06/perfboard-hackduino-arduino-compatible-circuit.jpg)

---

# Electronics Prototyping Platform
* Based on Atmel microcontrollers
* Lower level hardware and software concerns are abstractred away
* Minimal API differences accross hardware

![AVRs](http://www.open-homeautomation.com/wp-content/uploads/2013/04/797px-AVR_group-624x468.jpg)

---

background-image: url(images/avr_block_diagram.png)

---

background-image: url(images/avr_assembly.png)

---

# Arduino isn't scary!

.left[```c
int led = 13;

void setup() {
  pinMode(led, OUTPUT);

void loop() {
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}
```]

![blink](images/blink.jpg)

---

# Where to Begin?
* http://arduino.cc/en/Guide/HomePage
* Straightforward and lots of pictures

---

# Wires and Stuff
![breadboard](http://www.ladyada.net/images/arduino/bbunderside_t.jpg)

---

background-image: url(http://yourduino.com/Photos/BreadBoard-1.jpg)

---

background-image: url(https://dlnmh9ip6v2uc.cloudfront.net/r/600-600/assets/6/8/6/d/1/51cdc767ce395f7558000002.png)

---

# Voltage, Current, Resistance, and Ohm's Law
## V = I * R

![ohms_law](images/ohms_law.jpg)