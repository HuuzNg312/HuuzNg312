<div align="center">

# Huu Nguyen Phu

### Electronics & Telecommunications Undergraduate · Design Verification · RTL Design

[![Portfolio](https://img.shields.io/badge/Portfolio-0B1220?style=for-the-badge&logo=githubpages&logoColor=62D9FF)](https://huuzng312.github.io)
[![Email](https://img.shields.io/badge/Email-0B1220?style=for-the-badge&logo=gmail&logoColor=62D9FF)](mailto:huuz.sync312@gmail.com)

</div>

I am an Electronics and Telecommunications undergraduate at **HCMUTE (2024-2028)**, focused primarily on **Design Verification** and secondarily on **RTL Design**. I use project work to practice translating specifications into testable RTL, checking behavior against golden data, debugging failures, and documenting evidence.

I am working toward internship and graduate roles in **Design Verification** and **RTL Design**.

## Technical Focus

| Area | Practical experience |
|---|---|
| **Design Verification** | Directed Verilog testbenches, software golden-model comparison, layer-level checks, firmware/RTL co-simulation, waveform debug, end-to-end regression |
| **RTL Design** | Verilog, RV32I datapath and control, MMIO peripherals, signed fixed-point arithmetic, PE arrays, buffering, FSM-based control |
| **Project platforms & tools** | ModelSim/Questa, Tang Nano 20K, Gowin EDA, bare-metal C, Python, UART, SPI/microSD, Git |

## Featured Engineering Project

### [RISC-V Controlled INT8 CNN Accelerator on FPGA](https://github.com/HuuzNg312/riscv-int8-cnn-accelerator)

A three-member team project integrating an **RV32I processor**, a **4×4 signed-INT8 CNN accelerator**, raw-sector microSD storage, a CRC32-protected UART firmware loader, and HDMI visualization on the **Tang Nano 20K**.

- Conv1 and Conv2 run in RTL; pooling, requantization, fully connected layers, and Argmax run in bare-metal C.
- The PE array performs up to **16 INT8 × INT8 MAC operations per accelerator cycle** with INT32 accumulation.
- Verification includes directed RTL tests, integer golden data, an SDHC simulation model, and firmware-driven end-to-end inference.
- The exported integer pipeline classifies **98/100** included real handwritten-digit samples.
- Post-P&R evidence reports **76% logic**, **100% BSRAM**, and **92% DSP** utilization. Setup timing passes; 15 cross-domain hold endpoints remain open and are documented as a limitation.

> The repository and course report identify this as a three-person implementation. Module-level individual ownership is not claimed where the source material does not provide an auditable responsibility breakdown.

[Project README](https://github.com/HuuzNg312/riscv-int8-cnn-accelerator#readme) · [Technical report](https://github.com/HuuzNg312/riscv-int8-cnn-accelerator/blob/main/Final_Project.pdf) · [Portfolio project entry](https://huuzng312.github.io/#project-01)

## Additional Work

- **[Autonomous Line Following & Obstacle Avoiding Robot](https://github.com/HuuzNg312/Autonomous-Line-Following-Obstacle-Avoiding-Robot)** — Arduino-based mobile robot using reflectance and ultrasonic sensing with finite-state navigation.
- **[ESP32 Hardware & Peripheral Exercises](https://github.com/HuuzNg312?tab=repositories)** — UART, PWM, digital input, sensors, and PCB-oriented learning projects.

## Engineering Approach

I value clear interfaces, traceable verification evidence, and honest reporting of limitations. For each serious project, I aim to document the architecture, implementation decisions, tests, measured results, unresolved issues, and next steps—not only the final source code.

## Contact

- **Email:** [huuz.sync312@gmail.com](mailto:huuz.sync312@gmail.com)
- **Portfolio:** [huuzng312.github.io](https://huuzng312.github.io)
- **GitHub:** [@HuuzNg312](https://github.com/HuuzNg312)
