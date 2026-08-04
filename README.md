# 🪫Noire

> Building basic logic gates using discrete NPN transistors and resistor-transistor logic.

`noire` is a hardware-focused project exploring digital logic fundamentals by constructing basic gates—such as NOT, AND, and OR—using discrete NPN transistors and passive components. By implementing Resistor-Transistor Logic (RTL) on breadboards and Tinkercad simulations, it provides a hands-on look at how core computing operations function at the component level without integrated circuits.

---

## ⚡ Gate Implementations

| Logic Gate | Transistors | Circuit Behavior / Concept |
| :--- | :--- | :--- |
| **NOT Gate** | 1x NPN | Inverter using a common-emitter pull-down setup |
| **AND Gate** | 2x NPN | Transistors in series (both inputs must be HIGH to conduct) |
| **OR Gate** | 2x NPN | Transistors in parallel (either input HIGH conducts) |
---

## 🛠️ Hardware Stack

* **Active Components:** NPN Bipolar Junction Transistors (e.g., BC547 / 2N3904)
* **Power Supply:** LM7805 5V Voltage Regulator + 9V DC Source
* **Passives:** 1kΩ Base Resistors, 220Ω LED Limiters
* **Inputs & Indicators:** Push Button or slide switches, LEDs

---
💡Links to the Tinkercad simulations are provided in the simulations folder
---

## 📂 Repository Structure

```text
noire/
├── schematics/       # Circuit diagrams and schematics (.pdf)
├── simulations/      # Tinkercad workspace exports
└── docs/             # Truth tables & logic state descriptions
