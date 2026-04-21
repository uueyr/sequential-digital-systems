# Digital Logic Systems – Logisim Implementation

## Overview
This project implements a collection of fundamental digital logic circuits using Logisim, progressing from basic memory elements to more complex sequential systems.

The design follows a hierarchical approach, where simple components are composed to build higher-level digital systems.

## Implemented Modules

### Memory Elements
- SR Latch
- Clocked SR Latch
- D Latch
- D Flip-Flop
- D Flip-Flop with Reset

### Sequential Logic
- JK Flip-Flop (Asynchronous)
- Shift Register
- 4-bit Shift Register
- Clocked Shift Register (multi-stage)

### Combinational Logic
- Half Adder
- Full Adder

### Integrated Systems
- Serial Adder (using shift registers and full adder)
- Sequence Detector (finite state machine)

## Design Approach
- Built using **gate-level logic**
- Emphasis on **modularity and reuse**
- Higher-level circuits constructed from lower-level primitives
- Includes **clocked behavior and reset control**

## Key Concepts Demonstrated
- Feedback and state retention
- Clock-driven sequential logic
- Register-based data movement
- Bitwise arithmetic operations
- Finite state machine design

## Tools Used
- Logisim (digital logic simulator)

## File
- `.circ` file containing all modules and subcircuits

## Future Improvements
- Expand to ALU design
- Add pipelining concepts
- Implement synchronous state machines
- Optimize timing and propagation delays
