# Design-Implementation-of-FIR-Filter-on-FPGA(Ongoing)

## Overview

This repository contains the ongoing work on the **Design and Implementation of an FIR Filter on FPGA**. The project aims to develop an efficient and scalable FIR (Finite Impulse Response) filter architecture tailored for real-time DSP (Digital Signal Processing) applications such as adaptive filtering and communication systems.

## Project Highlights

- **Target Platform**: Xilinx Artix-7 Basys 3 Board (XC7A35TCPG236-1 FPGA)
- **Goals**:
  - Optimize FPGA resource utilization (DSP slices, LUTs, and BRAM).
  - Enable dynamic coefficient reconfiguration for adaptability.
  - Achieve high throughput with minimal latency.
- **Current Status**: 
  - Only the **DSP Unit** has been implemented.
  - Other components, such as the SIPO shift register, multiplexer, and control unit, will be developed in future phases.

## Key Features

- **Implemented**:
  - High-speed Multiply-Accumulate (MAC) operations using the DSP Unit.
- **Planned**:
  - Dynamic coefficient updates using BRAM.
  - Data flow optimization via SIPO shift registers and multiplexers.
  - Seamless integration of all components for full FIR filter functionality.

## Tools and Technologies

- **Hardware**:
  - FPGA: Xilinx Artix-7 Basys 3 Board
  - Core Components: DSP48A1 slices, LUTs, BRAM
- **Software**:
  - Vivado Design Suite for synthesis and simulation.
  - MATLAB for coefficient generation and validation.

## Progress and Results

- **Current Achievements**:
  - DSP Unit designed and validated for Multiply-Accumulate (MAC) operations.
- **Future Work**:
  - Implementation of the complete FIR filter architecture, including dynamic reconfiguration and control units.
  - Simulation and deployment on advanced FPGA platforms for improved performance.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Stay tuned for updates as we progress towards completing the design and achieving full functionality!
