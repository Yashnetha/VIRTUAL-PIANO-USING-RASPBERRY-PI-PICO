# 🎹 Touch-Sensor Virtual Piano using Raspberry Pi

This project implements a **portable virtual piano** using a Raspberry Pi, touch sensors, and other key components. It allows users to simulate playing a piano without physical keys, with audio output and real-time feedback.

---

## 📌 Features

- 🎵 **Touch-Sensitive Piano**: Play notes by touching sensor pads.
- 💡 **LCD Display**: Shows current mode and notes.
- 🔄 **Mode Switching**: Change instrument sounds or scales.
- 🔊 **High-Quality Audio**: Uses DF Mini Player for realistic sound.
- 🔋 **Portable Design**: Powered by a stable power supply for mobility.

---

## 🛠️ Components Used

- Raspberry Pi (any model with GPIO)
- Touch Sensor Module (e.g., TTP223 or capacitive touch module)
- DF Mini MP3 Player
- SD Card with MP3 notes
- LCD Display (e.g., 16x2 or 20x4)
- Speaker or headphones
- Power Supply (Battery/Adapter)
- Jumper wires and breadboard

---

## 📷 Project Preview

![Virtual Piano Image](images/virtual_piano.jpg)

---

## 🚀 How It Works

1. Touch sensors detect finger input.
2. Raspberry Pi reads the sensor state via GPIO.
3. Based on the touch, it triggers the corresponding piano note via DF Mini Player.
4. The LCD shows the current note or mode.
5. Mode changer lets you switch sound profiles or scales.

---

## 📂 Folder Structure

