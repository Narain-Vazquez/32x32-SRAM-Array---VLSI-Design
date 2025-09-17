# 32x32-SRAM-Array---VLSI-Design
This repository contains a complete 32x32 SRAM memory array design using CMOS technology. The design includes all necessary components for a functional SRAM cell array with peripheral circuitry for read/write operations.

all files on within the SRAM array folder should be able to interface with the cadence virtuoso enviroment

32x32_SRAM_Array/
├── schematics/         # Circuit schematics
│   ├── 6T_SRAM_cell/   # Single 6T SRAM cell
│   ├── sense_amp/      # Sense amplifier
│   ├── precharge/      # Precharge circuit
│   └── sram_array/     # Top-level 32x32 array
├── simulations/        # Simulation testbenches
│   ├── cell_tests/     # Individual cell tests
│   ├── functionality/  # Functional verification
│   └── performance/    # Performance analysis
└── outputs/            # Simulation results, reports

for a description and analysis on the design and noise margins of the basic components of the SRAM array: 
https://docs.google.com/document/d/1_PjBFhiG7GOykstiEpN5fAwwkg0l48LDWnhAPYzo-bQ/edit?usp=sharing
