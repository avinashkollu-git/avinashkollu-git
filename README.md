<h1 align="center">AVINASH KOLLU</h1>

<p align="center">
  <b>Silicon / RTL Design Engineer</b> &nbsp;|&nbsp; Electronics &amp; Communication Engineering (2026)
</p>

<p align="center">
  Digital design and silicon implementation. I build synthesizable RTL in Verilog,
  verify it with self-checking testbenches, and read the waveforms.
</p>

<p align="center">
  <a href="mailto:avinashkollu123@gmail.com"><img src="https://img.shields.io/badge/Email-avinashkollu123%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/openhwgroup/cve2/pull/334"><img src="https://img.shields.io/badge/OpenHW-CVE2%20Contributor-1f6feb?style=flat-square&logo=github&logoColor=white"></a>
  <img src="https://img.shields.io/badge/Focus-RTL%20%7C%20VLSI%20%7C%20Computer%20Architecture-1f6feb?style=flat-square">
</p>

---

### What I work on

- **RTL design** in Verilog: pipelines, FSMs, arbiters, serial interfaces
- **Computer architecture**: RISC-V, pipelining, forwarding, hazards, memory
- **Verification**: UVM (driver, monitor, scoreboard, golden reference model), constrained-random &amp; self-checking testbenches, waveform &amp; timing analysis
- **CDC**: gray-code pointers, multi-flop synchronizers, async FIFOs

I work with a fully open-source hardware flow: **Icarus Verilog** for simulation,
**GTKWave** for waveforms, and **Yosys** for synthesis checks, so every project
below both *simulates* and *synthesizes*.

---

### Featured Hardware Projects

| Project | What it is | Highlights |
|---|---|---|
| **[riscv-5stage-core](https://github.com/avinashkollu-git/riscv-5stage-core)** | 32-bit RV32I 5-stage pipelined CPU | Data forwarding, load-use stall, branch flush, bundled Python assembler, all tests pass |
| **[async-fifo](https://github.com/avinashkollu-git/async-fifo)** | Sync + async (CDC) FIFO | Gray-code pointers, 2-flop synchronizers, registered flags, 167/63 MHz verified |
| **[spi-master](https://github.com/avinashkollu-git/spi-master)** | Configurable SPI master | All four modes (CPOL/CPHA), programmable clock divider, full-duplex, verified both directions |
| **[uart-controller](https://github.com/avinashkollu-git/uart-controller)** | Parameterized 8N1 UART | Configurable baud, mid-bit sampling, input synchronizer, loopback tested |
| **[uvm-fifo-verification](https://github.com/avinashkollu-git/uvm-fifo-verification)** | UVM testbench for a sync FIFO | Layered UVM env (driver, monitor, scoreboard, golden-queue model), runs to PASS on Verilator + Accellera UVM (1326 checks, 0 errors) |

Each repo ships **RTL + self-checking testbench + waveform + README**, and runs with a
one-line `make test`.

---

### Systems &amp; Performance

| Project | What it is | Highlights |
|---|---|---|
| **[High-Performance-LLM-Systems](https://github.com/avinashkollu-git/High-Performance-LLM-Systems)** | Llama-3 inference on Apple M4 silicon | Roofline model of the memory-bandwidth ceiling, MLX benchmark harness (TTFT / decode tok/s / peak memory), quantization trade-offs |

The same reasoning silicon uses (arithmetic intensity, the memory wall, roofline
analysis), applied to real inference on Apple Silicon.

---

### Open Source

Contributions across three respected RISC-V organizations, spanning RTL, hardware documentation, and verification tooling:

- **[OpenHW CVE2 (RISC-V core)](https://github.com/openhwgroup/cve2/pull/334)** (merged): a maintainer-approved fix for IEEE 1800 `$fatal` standards compliance in OpenHW's CVE2 RISC-V core, re-verified by the maintainer on Verilator and Questa. Official **OpenHW Foundation Contributor**.
- **[OpenHW core-v-mcu](https://github.com/openhwgroup/core-v-mcu/pull/371)** (open PR): documented how the APB Timer implements the RISC-V machine timer (`mtime` / `mtimecmp`, MTIME), covering the register mapping and the firmware programming sequence, grounded in the RTL.
- **[CHIPS Alliance riscv-dv](https://github.com/chipsalliance/riscv-dv/pull/1035)** (open PR): a Python fix so the CSR test generator reads read-only CSRs instead of emitting illegal writes that hang the test, motivated by lowRISC/ibex#1337.

---

### Toolbox

<p>
  <img src="https://img.shields.io/badge/Verilog-HDL-orange?style=flat-square">
  <img src="https://img.shields.io/badge/SystemVerilog-HDL-orange?style=flat-square">
  <img src="https://img.shields.io/badge/UVM-verification-e11d48?style=flat-square">
  <img src="https://img.shields.io/badge/RISC--V-RV32I-283272?style=flat-square&logo=riscv&logoColor=white">
  <img src="https://img.shields.io/badge/Verilator-sim-3fb950?style=flat-square">
  <img src="https://img.shields.io/badge/Icarus%20Verilog-sim-3fb950?style=flat-square">
  <img src="https://img.shields.io/badge/GTKWave-waveforms-58a6ff?style=flat-square">
  <img src="https://img.shields.io/badge/Yosys-synthesis-yellow?style=flat-square">
  <img src="https://img.shields.io/badge/C-language-00599C?style=flat-square&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/Python-language-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/MLX-Apple%20Silicon-black?style=flat-square&logo=apple">
  <img src="https://img.shields.io/badge/MATLAB-signals-EE7422?style=flat-square">
  <img src="https://img.shields.io/badge/Git-vcs-F05032?style=flat-square&logo=git&logoColor=white">
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=avinashkollu-git&show_icons=true&hide_border=true&theme=github_dark" height="150">
</p>

<p align="center"><i>Open to Silicon / RTL Design Engineer (New Grad) roles.</i></p>
