# 🌌 AryaCode- Physical Computational Learning

<p align="center">

<img src="assets/images/logo.png" width="220">

</p>

<h3 align="center">
Ancient Astronomy. Physical Code. Modern Computational Thinking.
</h3>

<p align="center">
A screen-light physical programming game inspired by the mathematical and
astronomical heritage of Aryabhata.
</p>

---

## 📌 Overview

**Aryabhata's Observatory** is a physical coding and computational-thinking
game designed around the idea of learning programming through interaction
rather than conventional screen-based coding.

The player takes the role of an **apprentice astronomer**.

They receive an astronomy-based mission, interact with a physical celestial
dial, construct a program using tangible coding blocks, scan the blocks using
NFC/RFID, and press **RUN**.

An **ESP32** interprets the resulting program, executes it against the mission
inputs, checks the goal condition, and provides feedback through an OLED
display, addressable LED ring and optional buzzer.

# 🧩 Prototype & Workflow

## 🏗️ Prototype

The proposed Aryabhata's Observatory prototype is designed as a compact,
interactive physical coding station.

The prototype combines:

- A celestial dial for astronomical and numerical input
- NFC/RFID-enabled physical coding blocks
- An OLED display for missions and feedback
- Push buttons for interaction and execution
- An addressable LED ring for visual feedback
- An ESP32 as the central controller

<p align="center">
  <img src="assets/images/prototype.png"
       alt="Aryabhata's Observatory Prototype"
       width="700">
</p>

## Workflow

```text
Mission
   ↓
Celestial Dial
   ↓
Physical Coding Blocks
   ↓
NFC/RFID Scanning
   ↓
ESP32 Program Interpreter
   ↓
Program Execution
   ↓
Goal Checking
   ↓
OLED + LED + Buzzer Feedback
