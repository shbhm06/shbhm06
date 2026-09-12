<h1 align="center">Hi there, I'm Shubham</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=C792EA&center=true&vCenter=true&width=560&lines=FPGA+%2F+RTL+Design+Engineer;Hardware+Accelerator+Builder;ECG+%7C+Audio+DSP+%7C+CNN+on+Silicon" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shbhm06&style=flat-square&color=blueviolet" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/shbhm06?style=flat-square&color=blueviolet&label=followers" alt="Followers" />
</p>

<br>

## About

Electronics and Communication Engineering student at **NIT Rourkela**, building FPGA-based hardware accelerators from algorithm down to timing closure. I like taking published research papers and rebuilding them in hardware from scratch — currently working across DSP pipelines, CDC-safe FIFOs, and CNN inference on FPGA.

<br>

## Projects

**[ECG Arrhythmia Accelerator](https://github.com/shbhm06/ecg_accelerator_fpga)**
FPGA-based ECG arrhythmia classifier on Zynq XC7Z020 (PYNQ-Z2), based on Loh et al. (ASAP 2020). DWT preprocessing → 4-block CNN → dense classifier in Verilog RTL, Q4.8 fixed-point, 80% accuracy at 65 MHz via an AXI4-Stream wrapper.

**[FFT-Based Frequency-Domain Audio Equalizer](https://github.com/shbhm06/fft_audio_equalizer)** · *ongoing*
Pipelined radix-2 FFT/IFFT core in Verilog for frequency-domain audio equalization, with fixed-point butterfly units, a twiddle-factor ROM, and bit-reversal addressing — validated against a Python/NumPy golden model.

**[CNN Accelerator (MNIST)](https://github.com/shbhm06/cnn_accelerator_MNIST)**
Fully pipelined 10-layer CNN inference engine for real-time digit classification, 100 MHz timing closure on a Xilinx Kria KV260, with an AXI4-Stream wrapper and DMA backpressure handling.

**[Async FIFO (CDC-safe)](https://github.com/shbhm06/async_fifo)**
Parameterized 16×8-bit async FIFO using Cummings' 2002 CDC methodology — gray-coded pointers, 2-stage synchronizers, timing closure across 100/50 MHz domains, verified with SystemVerilog assertions.

**[UART_RXTX](https://github.com/shbhm06/UART_RXTX)**
UART transmitter/receiver module in Verilog.

<br>

## Tools & Technologies

**Languages** — Verilog · SystemVerilog · Python · C/C++

**FPGA & EDA** — Vivado · Quartus Prime · ModelSim · KiCad · Proteus · NI Multisim · MATLAB

**Libraries** — PyTorch · NumPy

**Other** — Git · Linux

<br>

## Experience & Achievements

- **Summer Research Intern, IIT Roorkee** (May – June 2026) — Architected a fully streaming Verilog RTL datapath for an FPGA-based ECG classifier (4-level DWT cascade + 4-layer 1D CNN), with parameterized 3-state FSMs for fixed-point MAC arithmetic and an AXI4-Stream co-design wrapper on a PYNQ-Z2, reaching 80% accuracy at 65 MHz.
- **ARM Bharat AI-SoC Student Challenge** (March 2026) — Developed hardware-accelerated CNNs for real-time object detection on Xilinx Zynq FPGAs.
- **Shaastra Analog Circuit Design Competition** — Certificate of participation.

<br>

## GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=shbhm06&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shbhm06&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<br>

## Connect

<p align="center">
  <a href="https://www.linkedin.com/in/shubham-shreekumar-521526272/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:shubham.shreekumar@gmail.com">Email</a>
</p>

<p align="center"><sub>From <a href="https://github.com/shbhm06">shbhm06</a> — building hardware, one module at a time.</sub></p>
