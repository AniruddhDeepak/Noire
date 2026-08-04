# Resistor-Transistor Logic (RTL) Principles

## Core Concept
Resistor-Transistor Logic (RTL) uses NPN bipolar junction transistors (BJTs) as voltage-controlled switches and passive resistors to create pull-up or current-limiting networks.

## Transistor States in Logic Circuits
1. **Cutoff Region (Logic 0 / Off):**
   * $V_{BE} < 0.7\text{V}$
   * No base current flows ($I_B = 0$).
   * Transistor acts as an **open switch**.

2. **Saturation Region (Logic 1 / On):**
   * $V_{BE} \approx 0.7\text{V}$
   * Base current drives the transistor fully ON ($V_{CE} \approx 0.2\text{V}$).
   * Transistor acts as a **closed switch** to Ground.

## Logic Inversion
Because an active NPN transistor connects its Collector down to its Emitter (Ground), the basic common-emitter configuration inherently acts as an **inverter (NOT operation)**. Non-inverting logic (AND, OR) is created by sampling across the load resistor or cascading inverted stages.
