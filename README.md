# LED Blink (Arduino Simulation)

This is my first IoT project using **Arduino Uno** on **Wokwi**.  
It makes an LED blink ON and OFF every 500 ms.

---

##  Components
- Arduino Uno (simulated)  
- LED  
- Resistor (220 Ω)  
- Wokwi online simulator

---

##  Code
```cpp
void setup() {
  pinMode(5, OUTPUT);
}

void loop() {
  digitalWrite(5, HIGH);
  delay(500);
  digitalWrite(5, LOW);
  delay(500);
}
