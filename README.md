# 32-bit Carry Lookahead Adder (VLSI Design)

> VLSI Project | CMOS Design | Tanner EDA | High-Speed Arithmetic Circuits

---

## Overview
Designed and implemented a 32-bit Carry Lookahead Adder (CLA) using a 250nm CMOS process. The project focuses on improving addition speed by reducing carry propagation delay compared to ripple-carry adders.

---

## Key Concepts
- Carry Lookahead Logic (Generate & Propagate)
- Parallel carry computation
- CMOS circuit design
- Transmission gate logic

---

## Architecture

- 4-bit CLA building block  
- 32-bit CLA using 8 cascaded 4-bit modules  
- Integrated 16-bit and 32-bit SIPO shift registers  
- Transmission gate-based logic  

---

## Design & Simulation

### CLA Schematic
![CLA](cla_schematic.png)

### Final 32-bit Design
![Final](final_design.png)

### Simulation Waveform
![Waveform](waveform.png)

---

## Tools Used
- Tanner EDA  
- HSPICE  
- CMOS 250nm process  

---

## Results

| Component | Delay | Power |
|----------|------|------|
| 4-bit CLA | ~590 ps | ~1.85 mW |
| 32-bit CLA | ~2.93 ns | ~16.6 mW |
| 16-bit SIPO | ~1.8 ns | ~6 mW |

---

## Key Learnings
- High-speed digital circuit design  
- CMOS layout and optimization  
- Trade-offs between delay, power, and area  
- Hierarchical hardware design  

---

