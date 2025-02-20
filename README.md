# Dual-Address ROM for High-Speed Memory Access

## Overview
This repository contains the Verilog implementation of a **Dual-Address ROM** optimized for high-speed memory access, particularly suited for **Gaussian function computation, image processing, and real-time FPGA applications**. The design incorporates:

- **Dual-Port ROM** for simultaneous access to spatial coordinates (`x, y`).
- **Memory Optimization** using Gaussian function symmetry to reduce storage requirements.
- **Pipeline Registers** to enhance timing performance and support higher clock speeds.
- **Clock-Gated Reads** to minimize power consumption.

## Features
- **Efficient Memory Usage**: Stores only precomputed Gaussian function values, reducing redundancy.
- **Parallel Access**: Dual-port ROM architecture allows simultaneous reads.
- **Low Latency**: Pipeline registers reduce critical path delay.
- **Power Efficiency**: Clock-gated memory reads reduce unnecessary power usage.
