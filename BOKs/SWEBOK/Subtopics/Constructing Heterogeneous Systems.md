---
tags:
  - swebok/subtopic
SWEBOK_Topic: "[[Construction Technologies]]"
---
Heterogeneous systems consist of a variety of specialized computational units of different types, such as:
- Digital Signal Processors (DSPs)
- microcontrollers
- peripheral processors.

These computational units are independently controlled and communicate with one another.

Embedded systems are typically heterogeneous systems.

The design of heterogeneous systems may require the combination of several specification languages in order to design different parts of the system—in other words, hardware/software codesign.

The key issues include:
- multilanguage validation
- cosimulation
- interfacing

During the hardware/software codesign, software development and virtual hardware development proceed concurrently through stepwise decomposition.

The hardware part is usually simulated in field programmable gate arrays (FPGAs) or application-specific integrated circuits (ASICs).
The software part is translated into a low-level programming language.