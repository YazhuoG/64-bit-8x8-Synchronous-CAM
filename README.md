# 64-bit (8×8) Synchronous CAM Design

## Project Overview

This project implements a 64-bit (8×8) synchronous Content Addressable Memory (CAM) using transistor-level and schematic-level design techniques.  
The design targets high-speed data search scenarios in embedded and hardware-accelerated systems.

Key objectives:
- Design CAM core and peripheral circuits  
- Perform schematic and layout design  
- Verify functionality and timing stability  
- Analyze match latency and critical path  

---

## Architecture

The CAM system consists of:

- CAM bitcell array  
- Bitline driver  
- Matchline logic  
- Decoder and encoder  
- Control logic  

The design supports parallel comparison to enable fast search operations.

*(Add architecture or bitcell diagram here if available)*

---

## Design Flow

The complete design flow includes:

1. Bitcell architecture analysis and selection  
2. Transistor-level schematic design  
3. Peripheral circuit design (decoder, drivers, matchline logic)  
4. Layout generation  
5. Functional simulation and timing verification  

Tools used:
- Synopsys Custom Compiler  
- HSpice  

---

## Verification

Verification steps included:

- Functional simulation of CAM search operations  
- Timing stability verification  
- Match latency analysis  
- Module-level simulation with different input patterns  

---

## Design Highlights

Key engineering aspects:

- Parallel search architecture for fast matching  
- Bitcell selection based on performance and area tradeoffs  
- Critical path analysis and optimization  
- Modular design for scalability  

---

## Repository Structure

Example structure:

/docs        Project reports and milestones  
/schematic   Schematic design files  
/layout      Layout files  
/sim         Simulation results  

---

## Skills Demonstrated

- Transistor-level circuit design  
- CAM architecture design  
- Schematic and layout design  
- Timing analysis  
- Circuit verification  

This project demonstrates practical ASIC circuit design and verification workflow.
