# Hi, I'm Sandeep Gorrepati 👋

**2025 ECE graduate** building and verifying digital hardware — targeting **Design Verification, RTL / Digital Design, and Pre-Silicon Validation** roles in the semiconductor industry.

📍 Bengaluru, India · open to relocation (India / Taiwan / Singapore / Malaysia)
🔗 LinkedIn: linkedin.com/in/sandeep-gorrepati-vlsi · ✉️ sandeep2gvn@gmail.com

## 🔧 What I work with
**Languages:** SystemVerilog, Verilog, Python, C/C++
**Verification:** UVM (driver / monitor / scoreboard / RAL), SVA, constrained-random, functional-coverage closure, cocotb
**Formal:** SymbiYosys + Z3 (k-induction)
**Protocols / Arch:** AXI4-Lite, APB, SPI, RV32I, 5-stage pipeline
**RTL / Flow:** RTL design, Verilator lint, Yosys synthesis, OpenROAD / Sky130, OpenSTA
**DFT:** scan insertion, stuck-at ATPG, fault coverage

Methodology is tool-agnostic and transferable to VCS / Questa / Xcelium and Verdi-style debug.

## 🚀 Proof projects (runnable + CI-tested)

| Project | What it shows | Result |
| --- | --- | --- |
| apb-regfile-cocotb | AMBA APB4 slave: cocotb BFM, scoreboard, coverage, PSLVERR error paths | 300 random txns, 0 mismatches, 100% coverage |
| spi-master-cocotb | SPI master, all 4 CPOL/CPHA modes: cocotb slave BFM, scoreboard | 48 transfers, 0 mismatches, 100% coverage |
| dft-scan-atpg | Full-scan insertion + from-scratch stuck-at ATPG / fault sim | 100% testable fault coverage, 9 patterns, 0 redundant |
| synth-sta | Yosys synthesis + OpenSTA timing (SDC, WNS / TNS) | gate-level netlist, critical-path analysis |
| ddr-controller-verification | RV32I + memory-controller verification, scoreboard checks | self-checking regressions, PASS/FAIL clean |

## 📫 Open to opportunities
Entry-level **DV / RTL / Validation / DFT** roles. Resume on request — happy to connect.
