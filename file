# 🔌 Raspberry Pi Relay Control System

This project allows a Raspberry Pi to control both **Solid State Relays (SSR)** and a **4-Channel Mechanical Relay Module**. It supports the switching of DC and AC loads using GPIO outputs, with proper isolation between logic and power domains.

---

## 🧰 Project Overview

### ▶️ Solid State Relays (8 Channels)

- Controlled via opto-isolators (e.g., PC817)
- Each channel includes a MOSFET switch for low-voltage loads
- Powered separately through **MOTOR_POWER** rails

### ⚙️ 4-Channel Mechanical Relay Module

- Relay coils driven by NPN transistors (e.g., 2N2222)
- Flyback diodes ensure safe operation
- Controlled using Raspberry Pi GPIOs
- Loads powered through **LED_POWER** rail

---

## 🎛️ Raspberry Pi GPIO Interface

A 40-pin Raspberry Pi header connects directly to the relay control circuits.

| Function         | GPIO Pins Used | Description                     |
|------------------|----------------|---------------------------------|
| SSR Outputs       | GPIO4–GPIO11   | Controls 8 SSR channels         |
| Relay Outputs     | GPIO17–GPIO20  | Controls 4 mechanical relays    |
| Power & Ground    | 3.3V, GND      | Logic power and grounding       |

Each GPIO is protected with a current-limiting resistor before driving the optocoupler or transistor.

---

## 🖼️ Schematic Overview

The system schematic is divided into three sections:

- **Solid State Relays (SSR)** — 8 individually controlled low-voltage channels  
- **4-Channel Relay Module** — Transistor-switched mechanical relays with flyback protection  
- **Raspberry Pi Connector** — Standard 40-pin header with GPIO mapped outputs

> 🔧 Refer to the schematic image in the repository for connection and wiring details.

---

## 👨‍💻 Author

**Muddessir Arif**  
📧 muddessirarif140174@gmail.com  
📞 +92 340 0586446  
🔗 [GitHub Profile](https://github.com/yourusername) <!-- Replace with actual GitHub link -->

---

> For questions or project collaboration, feel free to reach out.
