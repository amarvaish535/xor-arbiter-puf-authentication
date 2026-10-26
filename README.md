# XOR Arbiter PUF-Based Authentication System

## Project Overview
This project focuses on a hardware-based authentication system using an XOR Arbiter Physical Unclonable Function (PUF). PUF technology uses small physical variations in hardware to generate device-specific responses that can help identify and authenticate devices.

The project is implemented using Verilog HDL and evaluated through RTL simulation and FPGA-targeted analysis.

## Objectives
- Study Physical Unclonable Functions for hardware authentication.
- Design and simulate an XOR Arbiter PUF using Verilog HDL.
- Understand challenge-response pairs for device authentication.
- Analyze FPGA resource utilization and estimated power consumption.

## How It Works
1. A challenge is provided to the PUF design.
2. The challenge passes through the configured logic stages.
3. Multiple Arbiter PUF response bits are combined using XOR logic.
4. The resulting response can be used in a challenge-response authentication process.

## Tools and Technologies
- Verilog HDL
- Xilinx ISE
- ISim Simulator
- Xilinx XPower Analyzer
- FPGA target: Xilinx Artix-7 XC7A100T

## Implementation and Results
The current design was evaluated using simulation and FPGA-targeted resource and power analysis.

| Parameter | Current Design |
|---|---:|
| LUTs | 40 |
| Registers | 79 |
| Slices | 14 |
| Estimated total power | 85 mW |
| Estimated dynamic power | 3 mW |
| Estimated quiescent power | 82 mW |

**Note:** Power figures are tool-generated estimates, not measurements from a physical FPGA board. Physical PUF behavior has not yet been demonstrated.

## Applications
- IoT device authentication
- Hardware security
- Device identification
- Secure embedded systems

## Limitations and Future Work
- Validate physical PUF behavior on FPGA hardware.
- Study response reliability under different operating conditions.
- Obtain and analyze timing reports.
- Evaluate resistance to machine-learning-based modeling attacks.

## Project Status
RTL simulation and FPGA-targeted resource and power analysis.

## Team
Final-year Electronics and Communication Engineering project team.

## Keywords
XOR Arbiter PUF, Physical Unclonable Function, Hardware Security, Verilog HDL, FPGA, Authentication, IoT Security.
