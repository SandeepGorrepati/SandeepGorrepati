# Hi, I'm Sandeep Gorrepati

**Entry-Level Design Verification Engineer | SystemVerilog · UVM · SVA · Formal · cocotb**

2025 ECE graduate building and verifying digital hardware. My strongest work is in
protocol verification, self-checking testbenches, assertion-based verification,
functional coverage, formal property checking, RTL debug, and CPU microarchitecture.

India · targeting Bengaluru; open to relocation across India, Singapore, Malaysia and Taiwan  
[LinkedIn](https://linkedin.com/in/sandeep-gorrepati-vlsi) · sandeep2gvn@gmail.com

## Flagship engineering work

| Project | Engineering proof | Reproducible result |
|---|---|---|
| [AXI4-Lite UVM Verification](https://github.com/SandeepGorrepati/axi4lite-uvm-verification) | UVM agent, sequences, driver, monitor, reference-model scoreboard, coverage, SVA and formal response-policy proofs | Free Verilator UVM sanity/regression/RAL PASS; regression 344 writes/108 reads, zero errors; actual-DUT bounded formal (24 steps) |
| [RV32I 5-Stage Pipelined Core](https://github.com/SandeepGorrepati/rv32i-5stage-pipelined-core) | Pipeline RTL, forwarding, load-use stalls, branch flushing and reference-model instruction tests | 44 Python-oracle programs plus retirement/decode checks; writeback dependency bug found and fixed |
| [AI MAC-Array Verification](https://github.com/SandeepGorrepati/ai-mac-array-verification) | Signed 4×4 MAC matrix engine, saturation/overflow checking and independent Python model | Six parameter configurations, 2,022 Python-oracle matrix comparisons; 11 explicitly defined manual coverage bins |
| [SPI Master cocotb Verification](https://github.com/SandeepGorrepati/spi-master-cocotb) | Python slave BFM, scoreboard and all CPOL/CPHA combinations | 48 self-checked transfers, 0 mismatches |
| [DDR Controller Verification](https://github.com/SandeepGorrepati/ddr-controller-verification) | Simplified memory-controller verification with self-checking transaction and data-integrity tests | 2,200 traffic cycles and 1,329 read responses checked against a Python cycle oracle; not a full DDR controller |
| [AXI4-Lite to PCIe-Style Bridge](https://github.com/SandeepGorrepati/axi4-lite-pcie-bridge) | Educational AXI4-Lite-to-packet-interface RTL and FSM verification | 1,075 oracle write/read pairs; independent AW/W, AXI/packet stalls, error routing; not PCIe-compliant |
| [Synthesis and Netlist Equivalence](https://github.com/SandeepGorrepati/rtl-to-gdsii-openroad-flow) | Fresh generic synthesis, RTL/gate simulation, formal equivalence | 8,200 vectors per implementation; all 32 output equivalence bits proven; physical design remains exploratory |

## Technical stack

- **Verification:** UVM, constrained-random stimulus, functional coverage, SVA,
  reference-model scoreboards, regression automation, bug injection
- **Formal:** Yosys bounded SAT and combinational equivalence; separate simplified-policy SymbiYosys/Z3 induction experiments
- **RTL and architecture:** SystemVerilog, Verilog, RV32I pipelines, FSMs, AXI4-Lite,
  APB and SPI
- **Automation:** Python, cocotb, Make, GitHub Actions and Linux
- **Open-source flows:** Icarus Verilog, Verilator, Yosys, OpenSTA and OpenROAD

Commercial simulator names are not presented as hands-on experience; the repositories
focus on reproducible methodology using accessible tools.

## What I can discuss in an interview

- Root-causing RV32I branch decode and delayed-writeback defects from failing self-checking tests
- Designing AXI4-Lite monitors, response prediction, SVA and formal properties
- Closing functional-coverage gaps with directed tests
- Verifying signed arithmetic, saturation and pipeline latency in a MAC array
- Building protocol BFMs and reference models in SystemVerilog and Python

## Current target

Entry-level **Design Verification, Pre-Silicon Verification, RTL/Digital Design,
Emulation or hardware-heavy Validation** roles.
