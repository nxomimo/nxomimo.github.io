---
title: "Various Computer Systems Architecture Projects"
excerpt: "*Course assignments for Stanford's EE282: Computer Systems Architecture course, ranging from multi-core design to formal verification.*"
collection: portfolio
---

## Assignment 1: Multi-Core Design
This assignment involved four separate exercises for exploring performance, area, and energy trade-offs in the design of multi-core chips and multi-threaded applications. We simulated multi-core chips using Zsim on Google Cloud Computing, assessing performance across three separate application areas, including the black-scholes model and streamclustering.
- **Exercise 1: Throughput-Oriented Application Scalability**: Assessed application performance (using a metric of execution time) by varying cores from 1 to 8, then evaluated power and energy utilization.
- **Exercise 2: Core Complexity Mining**: Examined the relationship between core types (narrow vs. wide), performance, and energy consumption. Evaluated the optimal L2 cache size and associativity for the black-scholes application.
- **Exercise 3: Memory Hierarchy Tuning**: Evaluated varying technologies and L3 cache replacement techniques to optimize throughput across all applications.
- **Exercise 4: Finding an "Optimal" Multi-Core Design**: Used findings in the past three exercises to generate the "optimal" multi-core design for each of the three applications.

## Assignment 2: Register Renaming on a RISC-V Processor
Used **SystemVerilog** to implement the register renaming optimization into the source code of CVA6 (an open source RISC-V processor). 

## Assignment 3: Formal Verification
Formally verified aspects of the CVA6 implementation using JasperGold and the RISC-V Formal Interface (RVFI). More specifically, verified three specific instructions: ADD, LUI, and SW.