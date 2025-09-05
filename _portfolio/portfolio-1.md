---
title: "Music Synthesizer and Display on FPGA"
excerpt: "*Programming a PYNQ FPGA board to play a song from pure tones (sine waves) stored in memory, toggle between songs on button inputs, and display note waveforms on an external monitor.*<br/><img src='/images/fpga1.png' width='400'>"
collection: portfolio
---

![POV](/images/chordv.png){: .align-right width="290"}
This was my final project for EE108, Stanford's undergraduate course in digital systems design; my project team designed and implemented a real-time digital music synthesizer on a Xilinx PYNQ FPGA board.  

Key features included:  

- **Chords**: Enabled simultaneous playback of three notes by dynamically scheduling multiple waveform generators and mixing their outputs.  
- **Echo**: Added a delayed playback path to create reverberation effects with a 250 ms delay.  
- **Harmonics**: Layered scaled harmonic overtones (2×, 4×, and 8× the base frequency) onto each note to mimic organ-like timbres.  
- **Dynamics**: Implemented exponential amplitude decay, giving each note a more natural, instrument-like sound profile.  

These features were integrated through custom Verilog modules, finite state machines, and careful timing analysis to ensure glitch-free audio. The final system demonstrated how low-level digital design can be used to replicate high-level musical expression in hardware.