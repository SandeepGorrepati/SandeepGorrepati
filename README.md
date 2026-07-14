# Hi, I'm Sandeep Gorrepati

**Entry-Level Design Verification Engineer | SystemVerilog · UVM · SVA · Formal · cocotb**

2025 ECE graduate building and verifying digital hardware. My strongest work is in
protocol verification, self-checking testbenches, assertion-based verification,
functional coverage, formal property checking, RTL debug, and CPU microarchitecture.

Bengaluru, India · open to relocation across India, Singapore, Malaysia and Taiwan  
[LinkedIn](https://linkedin.com/in/sandeep-gorrepati-vlsi) · sandeep2gvn@gmail.com

## Flagship engineering work

| Project | Engineering proof | Reproducible result |
|---|---|---|
| [AXI4-Lite UVM Verification](https://github.com/SandeepGorrepati/axi4lite-uvm-verification) | UVM agent, sequences, driver, monitor, reference-model scoreboard, coverage, SVA and formal response-policy proofs | Self-checking regressions, bug injection and committed proof logs |
| [RV32I 5-Stage Pipelined Core](https://github.com/SandeepGorrepati/rv32i-5stage-pipelined-core) | Pipeline RTL, forwarding, load-use stalls, branch flushing and reference-model instruction tests | 14/14 self-checking instruction tests pass; real branch-decode bug found and fixed |
| [AI MAC-Array Verification](https://github.com/SandeepGorrepati/ai-mac-array-verification) | Signed 4×4 MAC matrix engine, saturation/overflow checking and independent Python model | Directed corners plus constrained-random tests and coverage closure |
| [SPI Master cocotb Verification](https://github.com/SandeepGorrepati/spi-master-cocotb) | Python slave BFM, scoreboard and all CPOL/CPHA combinations | 48 self-checked transfers, 0 mismatches |
| [DDR Controller Verification](https://github.com/SandeepGorrepati/ddr-controller-verification) | Simplified memory-controller verification with self-checking transaction and data-integrity tests | Runnable regression evidence; educational controller scope documented in the repository |
| [AXI4-Lite to PCIe-Style Bridge](https://github.com/SandeepGorrepati/axi4-lite-pcie-bridge) | Educational AXI4-Lite-to-packet-interface RTL and FSM verification | Protocol-translation demonstration; not a PCIe-compliant implementation |

## Technical stack

- **Verification:** UVM, constrained-random stimulus, functional coverage, SVA,
  reference-model scoreboards, regression automation, bug injection
- **Formal:** SymbiYosys, Z3 and k-induction
- **RTL and architecture:** SystemVerilog, Verilog, RV32I pipelines, FSMs, AXI4-Lite,
  APB and SPI
- **Automation:** Python, cocotb, Make, GitHub Actions and Linux
- **Open-source flows:** Icarus Verilog, Verilator, Yosys, OpenSTA and OpenROAD

Commercial simulator names are not presented as hands-on experience; the repositories
focus on reproducible methodology using accessible tools.

## What I can discuss in an interview

- Root-causing an RV32I branch `funct3` decode defect from a failing self-checking test
- Designing AXI4-Lite monitors, response prediction, SVA and formal properties
- Closing functional-coverage gaps with directed tests
- Verifying signed arithmetic, saturation and pipeline latency in a MAC array
- Building protocol BFMs and reference models in SystemVerilog and Python

## Current target

Entry-level **Design Verification, Pre-Silicon Verification, RTL/Digital Design,
Emulation or hardware-heavy Validation** roles.
