# LED Blink (Arduino Simulation)

This is my first IoT project using **Arduino Uno** on **Wokwi**.  
It makes an LED blink ON and OFF every 500 ms.

You can run this project directly on Wokwi:  
[▶️ Open Live Simulation](https://wokwi.com/projects/440509601830521857)

---

## 🛠 Components
- Arduino Uno (simulated)  
- LED  
- Resistor (220 Ω)  
- Wokwi online simulator  

---

## 💻 Code
```cpp
void setup() {
  pinMode(5, OUTPUT);
}

void loop() {
  digitalWrite(5, HIGH);  // Turn LED ON
  delay(500);             // Wait 500 ms
  digitalWrite(5, LOW);   // Turn LED OFF
  delay(500);             // Wait 500 ms
}

📚 What I Learned

- Basics of Arduino programming
- How to control digital outputs with digitalWrite()
- Using delay() to create timing in code
- How to simulate circuits using Wokwi
