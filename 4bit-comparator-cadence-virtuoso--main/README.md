# Design and Simulation of a 4-Bit Magnitude Comparator  
**Cadence Virtuoso | Full-Custom VLSI Design**

##  Project Overview
This project presents the complete **full-custom VLSI design and verification** of a
**4-bit magnitude comparator** implemented using **Cadence Virtuoso**.
The work follows a bottom-up design methodology, starting from basic logic gates and
ending with post-layout simulation using extracted parasitics.

The design flow includes:
- Schematic design
- Symbol generation
- Layout implementation
- Physical verification (DRC, LVS)
- Parasitic extraction (RCX)
- Post-layout simulation and validation

---

##  Functionality
The 4-bit magnitude comparator compares two 4-bit binary numbers **A** and **B** and
produces three outputs:
- **A > B**
- **A = B**
- **A < B**

Such comparators are fundamental building blocks in digital systems including
ALUs, processors, and decision-making circuits.

---

## 🛠 Tools & Technologies
- **Cadence Virtuoso**
- **Assura**
  - Design Rule Check (DRC)
  - Layout Versus Schematic (LVS)
  - Parasitic Extraction (RCX)
- **ADE L** (Analog Design Environment)

---

## Design Methodology
A **bottom-up hierarchical approach** was followed:

### 1. Basic Building Blocks
Individually designed, verified, and laid out:
- Inverter
- 2-input AND gate
- 3-input AND gate
- 4-input AND gate
- 2-input OR gate
- 4-input OR gate  

Each block includes:
- Schematic
- Symbol
- Layout
- LVS verification

### 2. Comparator Integration
- Hierarchical schematic construction using symbols
- Full layout assembly using verified sub-blocks
- Layout padding and routing for physical correctness

---

## Verification & Validation Flow
**Schematic-level transient simulation**  
**DRC** – Zero rule violations  
**LVS** – Layout matches schematic netlist  
**RCX** – Parasitic extraction using Assura  
**Average Extracted View generation**  
**Post-layout simulation with parasitics**

This ensures the design is functionally correct and physically reliable.

---

##  Simulation Results
- Input waveforms applied to all 4-bit inputs (A0–A3, B0–B3)
- Correct comparator output observed for all test cases
- Post-layout results closely match schematic-level behavior,
  confirming robustness under parasitic effects

---

##  Author
**Nadia Sultana**  
Department of Electrical and Electronic Engineering  
Chittagong University of Engineering and Technology

