# 🌙 Automatic Night Lamp using Arduino
This project demonstrates a simple Automatic Night Lamp using an Arduino UNO, an LDR (Light Dependent Resistor), and an LED. The lamp turns on automatically in the dark and turns off in the light.

## 🔧 Components Used:
- Arduino UNO

- Breadboard

- LDR (Light Dependent Resistor)

- 10kΩ Resistor (for LDR voltage divider)

- 220Ω Resistor (for LED protection)

- LED

- Jumper wires

## ⚙️ How it Works:
- The LDR detects ambient light.

- A voltage divider is used to convert the LDR readings into an analog signal readable by the Arduino.

- The Arduino reads the LDR value via analog pin A0.

- When the surrounding light is below a threshold, the LED turns ON, simulating a night lamp.

- When it is bright, the LED remains OFF.

## 💡 Arduino Code
The Arduino sketch for this project is saved in the file:
📂 `Automatic_Night_Lamp.ino`

## 📸 Demonstration Snapshot:
<img width="1414" height="754" alt="image" src="https://github.com/user-attachments/assets/e8c60d9c-c9a4-4e77-b840-b60c6f7eba8d" />
