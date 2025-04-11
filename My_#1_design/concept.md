# 🌈 MoodLight Magic

> A **light-reactive ambient lamp** that changes colors based on surrounding light.  
> No microcontroller. Just analog vibes, clever components, and ✨ creative circuitry.

---

## 🎯 Project Theme

Imagine a tiny ambient companion that responds to your environment.  
As day turns to night, the light adapts—beaming calming blues in brightness and cozy reds in the dark.

> It's a **jar of mood**, an analog soul reacting to the world around it.

---

## 🧠 The Idea

Use a **photoresistor (LDR)** and some basic components to:
- Detect surrounding light
- Drive an **NPN transistor** to switch between different **LEDs**
- Create a **mood lamp** without the need for any microcontroller

---

## ⚙️ Components

| Quantity | Component | Description |
|----------|-----------|-------------|
| 1x | Photoresistor (GL5528) | Senses ambient light |
| 1x | NPN Transistor (2N3904) | Acts as switch |
| 2x | LEDs (e.g., Red + Blue) | For mood lighting |
| 1x | 10kΩ Resistor | For voltage divider |
| 1x | 1kΩ Resistor | For transistor base |
| 2x | 220Ω Resistors | LED current limiting |
| 1x | Breadboard | Circuit prototyping |
| 1x | Power Source | 3V–5V (battery or USB) |
| Jumper Wires | – | For connections |

---

## 🧪 How It Works

```plaintext
[ Light Sensor ] + [ Resistor ] → Voltage Divider → Transistor Base
                ↓                      |
            Ambient Light        Controls LED behavior

