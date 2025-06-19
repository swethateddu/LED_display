# 🔴 LED Message Display Board

This project showcases a **programmable LED matrix display** using an Arduino and an 8x8 LED matrix module with a MAX7219 driver. It scrolls or flashes messages like "HELLO" or "TEMP" using simple Arduino code. Ideal for beginners looking to explore LED matrix control and create an eye-catching digital signage system.

---

## 🧠 Overview

- 🔢 Displays static or scrolling messages
- 💡 Controls an 8x8 LED Matrix with the MAX7219 driver
- 🕹️ Programmed via Arduino Uno or Nano
- 📟 Real-time character rendering using the LedControl library

---

## 📚 Learning Outcomes

- Understand how LED matrices work (rows, columns, scanning)
- Learn how to control individual LEDs using a microcontroller
- Create a functional mini digital signage system

---

## 🛠️ Requirements

### 🔌 Hardware
| Component                        | Quantity |
|----------------------------------|----------|
| Arduino Uno/Nano                 | 1        |
| MAX7219-based 8x8 LED Matrix     | 1        |
| Jumper wires                     | ~10      |
| Breadboard (optional)           | 1        |
| USB cable for Arduino           | 1        |

### 💾 Software
- Arduino IDE (https://www.arduino.cc/en/software)
- LedControl Library (install via Library Manager)

---

## 🔧 Wiring Instructions

| LED Matrix Pin | Arduino Pin |
|----------------|-------------|
| VCC            | 5V          |
| GND            | GND         |
| DIN            | D11         |
| CS             | D10         |
| CLK            | D13         |

> ✅ These are the default SPI pins for most Arduino boards.

---

## 📥 Setup & Upload

1. Connect the LED matrix to Arduino as per the wiring table.
2. Open `Arduino IDE`, install the **LedControl** library.
3. Paste the code from [led_display.ino](#) into the IDE.
4. Upload it to your Arduino.
5. Watch your message flash on the display!

---

