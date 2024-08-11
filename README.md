**MIPS32 Pipeline Processor**
This project implements a MIPS32 pipeline processor using Verilog. The implementation is verified using Icarus Verilog for simulation and GTKWave for waveform analysis. The MIPS32 model supports basic arithmetic operations, as confirmed by the provided test bench.

**Table of Contents**
-#Introduction.
-#Features.
-Project Structure.
-Setup and Simulation.
-Usage.
-Waveform Analysis.
-Test Bench.
-Contributing.
-License.
**Introduction**
This project demonstrates the design and simulation of a MIPS32 pipeline processor. The processor is capable of executing basic arithmetic operations with a simple pipelined architecture. The implementation is written in Verilog and can be simulated using Icarus Verilog, with results viewable in GTKWave.

**Features**
Five-stage pipeline: The processor includes the following stages:
Instruction Fetch (IF)
Instruction Decode (ID)
Execution (EX)
Memory Access (MEM)
Write Back (WB)
Basic arithmetic operations: Supports ADD, SUB, AND, OR, SLT, and MUL operations.
Memory operations: Supports load and store instructions.
Branching: Handles conditional branches with simple branch prediction (branch delay slots).

**Setup and Simulation**
**Prerequisites**
Ensure you have the following installed:
Icarus Verilog: A Verilog simulation tool.
GTKWave: A waveform viewer

**Test Bench**
Add three numbers 10 20 and 30  stored in registers 
