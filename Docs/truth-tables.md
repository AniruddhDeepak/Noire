# Logic Gate Truth Tables & Behavior

This document details the expected input/output behaviors for each NPN transistor logic gate implemented in `noire`.

---

## 1. NOT Gate (Inverter)

The output is always the inverse of the input.

| Input (A) | Output (Y) | Transistor State | LED State |
| :---: | :---: | :---: | :---: |
| 0 (LOW) | 1 (HIGH) | OFF (Cutoff) | ON |
| 1 (HIGH) | 0 (LOW) | ON (Saturation) | OFF |

---

## 2. AND Gate

Output is HIGH only when **both** inputs are HIGH.

| Input A | Input B | Output (Y) | Circuit State |
| :---: | :---: | :---: | :---: |
| 0 | 0 | 0 | Both transistors OFF |
| 0 | 1 | 0 | Q1 OFF, Q2 ON |
| 1 | 0 | 0 | Q1 ON, Q2 OFF |
| 1 | 1 | 1 | Both transistors ON (Series conduction) |

---

## 3. OR Gate

Output is HIGH if **at least one** input is HIGH.

| Input A | Input B | Output (Y) | Circuit State |
| :---: | :---: | :---: | :---: |
| 0 | 0 | 0 | Both transistors OFF |
| 0 | 1 | 1 | Q2 conducts to output |
| 1 | 0 | 1 | Q1 conducts to output |
| 1 | 1 | 1 | Both transistors conduct |

---
