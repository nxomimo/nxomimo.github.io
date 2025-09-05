---
title: "Music Synthesizer and Display on FPGA"
excerpt: "*Programming a PYNQ FPGA board to play a song from pure tones (sine waves) stored in memory, toggle between songs on button inputs, and display note waveforms on an external monitor.*<br/><img src='/images/fpga1.png' width='400'>"
collection: portfolio
---

## Overview
![POV](/images/chordv.png){: .align-right width="290"}
This was my final project for EE108, Stanford's undergraduate course in digital systems design; my project team designed and implemented a real-time digital music synthesizer on a Xilinx PYNQ FPGA board.  

Key features included:  

- **Chords**: Enabled simultaneous playback of three notes by dynamically scheduling multiple waveform generators and mixing their outputs.  
- **Echo**: Added a delayed playback path to create reverberation effects with a 250 ms delay.  
- **Harmonics**: Layered scaled harmonic overtones (2×, 4×, and 8× the base frequency) onto each note to mimic organ-like timbres.  
- **Dynamics**: Implemented exponential amplitude decay, allowing for the music to be output at varying volumes.

These features were integrated through custom Verilog modules, finite state machines, and careful timing analysis.

## Key Skills
- **Verilog HDL**: Designed custom modules (chords, echo, harmonics, dynamics) with FSM-based control.  
- **Digital Systems Design**: Experience with timing analysis, pipelining, and modular hardware architecture.  
- **FPGA Development**: Implemented and tested on Xilinx PYNQ board with on-board peripherals.  
- **Signal Processing**: Applied concepts like harmonic synthesis, exponential decay envelopes, and waveform mixing.  
- **Simulation & Verification**: Built testbenches to validate module functionality before hardware deployment.  
