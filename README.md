<div align="center">
  <img src="./assets/hero.svg" alt="Zhenshuo Zhang — Electronic Engineering, FPGA, RTL Design, Digital IC and AI Hardware" width="100%" />

  <p><strong>Electronic Engineering undergraduate · Digital hardware enthusiast · Exploring neuromorphic computing</strong></p>

  <a href="mailto:zz7y24@soton.ac.uk"><img src="https://img.shields.io/badge/University_Email-zz7y24%40soton.ac.uk-0B233D?style=flat-square&logo=gmail&logoColor=cyan" alt="University email" /></a>
  <a href="https://github.com/Lugu200510"><img src="https://img.shields.io/badge/GitHub-Lugu200510-0B233D?style=flat-square&logo=github&logoColor=white" alt="GitHub profile" /></a>
  <img src="https://img.shields.io/badge/Focus-FPGA_%7C_RTL_%7C_AI_Hardware-123A54?style=flat-square" alt="Engineering focus" />
</div>

---

### `01 // About me`

I'm **Zhenshuo Zhang**, a **BEng Electronic Engineering** student at the **University of Southampton, UK** (**expected graduation: 2027**).

My main interests are **FPGA implementation, RTL design and verification, digital integrated circuits, and hardware acceleration for machine learning**. I enjoy translating algorithms and system requirements into digital architectures that can be simulated, verified and tested on hardware.

I am currently exploring **spiking neural network (SNN) inference on FPGA** for biomedical signal classification as part of my undergraduate research project.

### `02 // Technical toolkit`

| Area | Technologies / experience |
|:--|:--|
| **RTL & FPGA** | Verilog HDL · FPGA design · simulation and testbenches · Intel Quartus · ModelSim |
| **IC design & verification** | Digital logic · finite-state machines · UART / APB · IC layout, DRC / LVS / PEX workflows |
| **Embedded systems** | C · microcontrollers · UART · SPI · RS-485 · sensors and displays |
| **Algorithms & ML** | Python · NumPy · MATLAB · machine learning coursework · SNN / LIF models (ongoing research) |
| **Development environment** | Git · VS Code · Linux / WSL2 · Jupyter Notebook |

### `03 // Engineering projects`

<table>
<tr>
<td width="50%" valign="top">
<h3>◈ Custom Digital IC — Tapeout &amp; Test</h3>
<p><code>Fabricated · Tested</code></p>
<p>Participated in a digital IC design and implementation workflow, including schematic/layout work, physical verification (DRC, LVS and PEX), and post-fabrication testing. The chip was fabricated and successfully tested.</p>
<p><b>Topics:</b> Digital IC · Physical Design · Verification</p>
</td>
<td width="50%" valign="top">
<h3>◈ FPGA FIR Filter</h3>
<p><code>Completed academic project</code></p>
<p>Developed a 16-tap, 16-bit fixed-point FIR filter architecture using a sequential multiply–accumulate datapath in Verilog, with simulation and hardware-oriented control logic.</p>
<p><b>Topics:</b> FPGA · Verilog · DSP · FSM</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>◈ Embedded Seat-Node System</h3>
<p><code>Academic team project</code></p>
<p>Worked on an embedded node with a graphical display, keypad, sensors and RS-485 messaging, including user interaction and communication functionality.</p>
<p><b>Topics:</b> Embedded C / Microcontrollers · Interfaces · Networking</p>
</td>
<td width="50%" valign="top">
<h3>◈ FPGA-Based SNN for Biomedical Classification</h3>
<p><code>Undergraduate research · In progress</code></p>
<p>Investigating a digital inference pipeline for biomedical signals: public datasets, host-side preprocessing/training, and FPGA implementation of spiking neural network inference.</p>
<p><b>Topics:</b> SNN · LIF Neurons · FPGA · Biomedical Signals</p>
</td>
</tr>
</table>

### `04 // Current research direction`

**FPGA-Based Spiking Neural Network for Biomedical Signal Classification**  
*Research project in progress — architecture below describes the intended workflow, not completed measured results.*

```mermaid
flowchart LR
    A[Public biomedical data] --> B[Preprocess and train on PC]
    B --> C[Export model parameters]
    C --> D[FPGA SNN inference]
    D --> E[Class prediction]
```

My research interests include **leaky integrate-and-fire (LIF) neurons**, **surrogate-gradient learning**, and the trade-offs between **accuracy, latency and FPGA resource usage**. Experimental performance numbers will be shared only after measurement.

### `05 // Other technical exploration`

- **Hybrid DQN–TD3 reinforcement learning for autonomous navigation** — paper reproduction / experimental work in progress using Python and a Linux-based development environment.
- **Hardware design practice** — parameterised Verilog modules, self-checking testbenches, UART/APB components, FIFOs and verification workflows.

### `06 // Connect`

- **GitHub:** [github.com/Lugu200510](https://github.com/Lugu200510)
- **University email:** [zz7y24@soton.ac.uk](mailto:zz7y24@soton.ac.uk)

<div align="center">
  <sub>From RTL and silicon to intelligent digital hardware.</sub>
</div>

