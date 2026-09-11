<h1 align="center">Hi there, I'm Shubham</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=C792EA&center=true&vCenter=true&width=600&lines=FPGA+%2F+RTL+Design+Engineer;Hardware+Accelerator+Builder;ECG+%7C+Audio+DSP+%7C+CNN+on+Silicon;Turning+Research+Papers+into+RTL" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shbhm06&style=flat-square&color=blueviolet" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/shbhm06?style=flat-square&color=blueviolet" alt="Followers" />
</p>

---

### About Me

- Electronics and Communication Engineering student at **NIT Rourkela**
- I design **FPGA-based hardware accelerators** — from algorithm, to fixed-point modeling, to RTL, to timing closure
- I like taking published research papers and **rebuilding them in hardware from scratch**, end to end
- Currently deep in DSP pipelines, CDC-safe FIFOs, and CNN inference on FPGA
- Always open to talking hardware design, digital VLSI, or embedded ML

---

### Featured Projects

<table>
<tr>
<td width="50%">

**[ECG Arrhythmia Accelerator](https://github.com/shbhm06/ecg_accelerator_fpga)**
FPGA-based ECG arrhythmia classifier targeting Zynq XC7Z020, based on the Loh et al. (ASAP 2020) paper. Full hardware-software co-design: DWT preprocessing → 4-block CNN → dense classifier, all in Verilog RTL with Q4.8 fixed-point quantization.

</td>
<td width="50%">

**[Parameterized FFT Audio Equalizer](https://github.com/shbhm06/fft_audio_equalizer)**
Generic-N FFT-based audio equalizer (FFT → per-bin gain → IFFT) reusing a single FFT core for forward/inverse. Verified against a bit-accurate Python golden model with Q1.15 fixed-point RTL.

</td>
</tr>
<tr>
<td width="50%">

**[CNN Accelerator (MNIST)](https://github.com/shbhm06/cnn_accelerator_MNIST)**
Fully pipelined 10-layer CNN inference engine in Verilog RTL for real-time 10-class digit classification, achieving timing closure at 100 MHz on a Xilinx Kria KV260. Uses optimized circular line buffers (140 bytes on-chip) and an AXI4-Stream wrapper with DMA backpressure handling.

</td>
<td width="50%">

**[Async FIFO (CDC-safe)](https://github.com/shbhm06/async_fifo)**
Parameterized 16×8-bit asynchronous FIFO built using Cummings' 2002 clock-domain-crossing methodology — gray-coded pointers with 2-stage synchronizers, timing closure across 100/50 MHz domains, and SystemVerilog assertions validating full/empty edge cases.

</td>
</tr>
<tr>
<td colspan="2">

**[UART_RXTX](https://github.com/shbhm06/UART_RXTX)**
UART transmitter/receiver module implemented in Verilog.

</td>
</tr>
</table>

---

### Tools & Technologies

<p align="left">
  <img src="https://img.shields.io/badge/Verilog-003366?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SystemVerilog-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Vivado-CC0000?style=for-the-badge&logo=xilinx&logoColor=white" />
  <img src="https://img.shields.io/badge/Quartus%20Prime-6C4C9B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ModelSim-1E5288?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" />
  <img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white" />
  <img src="https://img.shields.io/badge/Proteus-00A651?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NI%20Multisim-004A98?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

### Experience & Achievements

- **Summer Research Intern, IIT Roorkee** (May 2026 – June 2026) — Architected a fully streaming Verilog RTL datapath for an FPGA-based ECG classifier (4-level DWT cascade + 4-layer 1D CNN), with parameterized 3-state FSMs for fixed-point MAC arithmetic and an AXI4-Stream co-design wrapper on a PYNQ-Z2, reaching 80% accuracy at 65 MHz.
- **ARM Bharat AI-SoC Student Challenge** (March 2026) — Developed hardware-accelerated CNNs for real-time object detection on Xilinx Zynq FPGAs.
- **Shaastra Analog Circuit Design Competition** — Certificate of participation.

---

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=shbhm06&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shbhm06&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shbhm06&theme=tokyonight&hide_border=true" />
</p>

---

### Connect with Me

<p align="center">
  <a href="https://linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:YOUR-EMAIL@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center"><i>From <a href="https://github.com/shbhm06">shbhm06</a> — building hardware, one module at a time.</i></p>
