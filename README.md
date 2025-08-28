# LED-Blink-Arduino
Basic LED Blink simulation using Arduino on Wokwi. This project demonstrates digital output control with digitalWrite() and delay().

# LED Blink (Arduino Simulation)

This is my first IoT project using Arduino on **Wokwi**.  
It makes an LED blink ON and OFF with a 500ms delay.

## 🛠 Components
- Arduino Uno (simulated)
- 1x LED
- 1x Resistor (220Ω)
- Wokwi online simulator

## 💻 Code
```cpp
void setup() {
  pinMode(5, OUTPUT);  // Set pin 5 as output
}

void loop() {
  digitalWrite(5, HIGH); // Turn LED ON
  delay(500);            // Wait 500 ms
  digitalWrite(5, LOW);  // Turn LED OFF
  delay(500);            // Wait 500 ms
}

