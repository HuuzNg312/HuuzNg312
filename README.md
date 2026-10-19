<div align="center">

# Huu Nguyen Phu

### Electronics & Telecommunications Undergraduate · RTL · Design Verification · FPGA · Embedded Systems

[![Portfolio](https://img.shields.io/badge/Portfolio-0B1220?style=for-the-badge&logo=githubpages&logoColor=62D9FF)](https://huuzng312.github.io)
[![Email](https://img.shields.io/badge/Email-0B1220?style=for-the-badge&logo=gmail&logoColor=62D9FF)](mailto:huuz.sync312@gmail.com)

</div>

I am an Electronics and Telecommunications undergraduate at **HCMUTE (2024-2028)**, building practical experience across digital hardware, FPGA systems, verification, and embedded software. My current work focuses on taking designs from architecture and RTL through simulation, firmware integration, place-and-route analysis, and board-level demonstration.

I am working toward internship and graduate roles in **Design Verification, RTL Design, FPGA Engineering, and Embedded Systems**.

## Technical Focus

| Area | Practical experience |
|---|---|
| **RTL & digital design** | Verilog, RV32I datapath and control, MMIO peripherals, signed fixed-point arithmetic, PE arrays, buffering, FSM-based control |
| **Verification** | Directed Verilog testbenches, software golden-model comparison, layer-level checks, firmware/RTL co-simulation, end-to-end regression |
| **FPGA development** | Tang Nano 20K, Gowin EDA, synthesis, place-and-route, resource analysis, timing review, board bring-up |
| **Embedded systems** | Bare-metal C, UART, SPI/microSD, memory-mapped I/O, firmware loading, hardware-software integration |
| **Programming & tools** | C, C++, Python, Git, ModelSim/Questa, Gowin EDA, VS Code |

## Featured Engineering Project

### [RISC-V Controlled INT8 CNN Accelerator on FPGA](https://github.com/HuuzNg312/riscv-int8-cnn-accelerator)

A three-member team project integrating an **RV32I processor**, a **4×4 signed-INT8 CNN accelerator**, raw-sector microSD storage, a CRC32-protected UART firmware loader, and HDMI visualization on the **Tang Nano 20K**.

- Conv1 and Conv2 run in RTL; pooling, requantization, fully connected layers, and Argmax run in bare-metal C.
- The PE array performs up to **16 INT8 × INT8 MAC operations per accelerator cycle** with INT32 accumulation.
- Verification includes directed RTL tests, integer golden data, an SDHC simulation model, and firmware-driven end-to-end inference.
- The exported integer pipeline classifies **98/100** included real handwritten-digit samples.
- Post-P&R evidence reports **76% logic**, **100% BSRAM**, and **92% DSP** utilization. Setup timing passes; 15 cross-domain hold endpoints remain open and are documented as a limitation.

> The repository and course report identify this as a three-person implementation. Module-level individual ownership is not claimed where the source material does not provide an auditable responsibility breakdown.

[Project README](https://github.com/HuuzNg312/riscv-int8-cnn-accelerator#readme) · [Technical report](https://github.com/HuuzNg312/riscv-int8-cnn-accelerator/blob/main/Final_Project.pdf) · [Portfolio case study](https://huuzng312.github.io/#featured-project)

## Additional Work

- **[Autonomous Line Following & Obstacle Avoiding Robot](https://github.com/HuuzNg312/Autonomous-Line-Following-Obstacle-Avoiding-Robot)** — Arduino-based mobile robot using reflectance and ultrasonic sensing with finite-state navigation.
- **[ESP32 Hardware & Peripheral Exercises](https://github.com/HuuzNg312?tab=repositories)** — UART, PWM, digital input, sensors, and PCB-oriented learning projects.

## Development Journey

```text
2024  Electronics & Telecommunications foundations
2025  Embedded control, sensors, robotics, and PCB practice
2026  RV32I SoC, INT8 accelerator RTL, verification, FPGA integration
Next  Broader functional coverage, CDC cleanup, reusable verification environments
```

## Engineering Approach

I value clear interfaces, traceable verification evidence, and honest reporting of limitations. For each serious project, I aim to document the architecture, implementation decisions, tests, measured results, unresolved issues, and next steps—not only the final source code.

## Contact

- **Email:** [huuz.sync312@gmail.com](mailto:huuz.sync312@gmail.com)
- **Portfolio:** [huuzng312.github.io](https://huuzng312.github.io)
- **GitHub:** [@HuuzNg312](https://github.com/HuuzNg312)
