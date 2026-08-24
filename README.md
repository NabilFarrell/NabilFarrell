# Hi, I'm Muhammad Nabil Farrell 👋

Industrial Automation Engineer specializing in PLC programming, OPC UA communication, and HMI/SCADA systems.

## About Me

- 🔧 Building automation systems with CODESYS (ST, LD) and OpenPLC on ESP32
- 📡 Integrating OPC UA for real-time industrial communication
- 🖥️ Designing HMI dashboards with Node-RED
- ⚡ Validating open-source PLC alternatives against commercial hardware
- 🌱 Learning more about SCADA, Modbus TCP, and industrial IoT

## Featured Projects

### ⚡ [OpenPLC ESP32 vs Commercial PLC: DC Motor Control](https://github.com/NabilFarrell/openplc-esp32-motor-control)
ESP32 running OpenPLC validated against commercial PLCs (Siemens S7-1214C, Omron CP1L, WAGO PFC200)

- 3-Tier empirical benchmarking: scan cycle stability, I/O latency, integrated motor control
- ESP32 achieved ~1 ms scan cycle with 6.0 µs jitter — meets/exceeds $500+ commercial PLCs
- 750 continuous sessions (~6.5 hours) with zero degradation
- Bachelor's thesis at Hasanuddin University

### 🏭 [Feedmill Batching Control](https://github.com/NabilFarrell/feedmill-batching-control)
PLC state machine (CODESYS ST/LD) → OPC UA → Node-RED HMI dashboard

- 6-state batch process with 4 recipes (Poultry, Pig Growler, Pig Finisher)
- Safety interlocks: E-Stop latching, gate mutual exclusion, mixer safety
- Alarm system: Empty Bin, Underweight, Emergency Stop
- Real-time industrial dashboard with dark theme

## Tech Stack

| Category | Technologies |
|----------|-------------|
| **PLC Programming** | CODESYS V3.5, OpenPLC v3, IEC 61131-3 (ST, LD) |
| **Platforms** | ESP32 (FreeRTOS), Siemens S7, Omron CP |
| **Communication** | OPC UA, Symbol Set Configuration |
| **HMI/SCADA** | Node-RED Dashboard, node-red-contrib-opcua |
| **Measurement** | Oscilloscope, Arduino DAQ, Python (NumPy, Matplotlib) |
| **Tools** | Git, GitHub, VS Code |

## Let's Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/nabil-farrell/)
- 📧 nabilfarrellid@gmail.com
- 🐙 [GitHub](https://github.com/NabilFarrell)
