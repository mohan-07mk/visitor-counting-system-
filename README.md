# 👥 Visitor Counter with OLED Display using Arduino

A simple Arduino-based project that counts people entering and exiting a room using two IR sensors and displays the live count on an OLED screen.

## 🧰 Components Used
- Arduino UNO/Nano
- 2x IR Sensors
- 0.96" I2C OLED Display
- (Optional) Buzzer
- Breadboard + Jumper Wires

## 🔌 Circuit Diagram
*(Add image of circuit here or link to Fritzing file)*

## 💡 Working Principle
- IR Sensor 1 triggers when someone enters
- IR Sensor 2 triggers when someone exits
- Count is increased/decreased based on entry/exit logic
- Display updated live on OLED

## 📸 Output Screenshot
*(Add a photo of your working hardware)*

## 🧾 Code
Code is inside visitor_counter.ino file.

## 🧠 Future Scope
- Add relay to control fan/lights based on count
- Send data to cloud using ESP32
- Add RTC for time-based logging
