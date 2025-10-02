# BabySoC Functional Modelling

## 📌 Objective

To understand **System-on-Chip (SoC) fundamentals** and practice **functional modelling** of the BabySoC using simulation tools:

-   **Icarus Verilog (iverilog)** for compiling and simulating Verilog modules.
    
-   **GTKWave** for analyzing waveforms (.vcd).

## 📂 Project Structure
VSDBabySoC/
├── src/
│   ├── include/             # Header files and parameter definitions
│   ├── module/              # RTL source files
│   │   ├── vsdbabysoc.v     # Top-level SoC
│   │   ├── rvmyth.v         # RISC-V core
│   │   ├── avsdpll.v        # PLL module
│   │   ├── avsddac.v        # DAC module
│   │   ├── clk_gate.v       # Clock gating logic
│   │   ├── pseudo_rand.sv   # Random generator
│   │   ├── pseudo_rand_gen.sv
│   │   └── testbench.v      # Main testbench
└── output/                  # Simulation outputs
