# Dual-Clock-Asynchronous-FIFO
FIFOs are often used to safely pass data from one clock domain to another asynchronous clock domain. Using a FIFO to pass data from one clock domain to another clock domain requires multi-asynchronous clock design techniques. An asynchronous FIFO refers to a FIFO design where data values are written to a FIFO buffer from one clock domain and the data values are read from the same FIFO buffer from another clock domain, where the two clock domains are asynchronous to each other.
***Simulation Results***
<img width="959" alt="Simulation" src="https://github.com/user-attachments/assets/690ceac9-5c41-4f1a-bc83-4ccdad2fab19">

***Conclusion**
◦ Designed Asynchronous FIFO in Verilog, synthesised & verified the design inn ModelSim.
◦ Synchronization of FIFO pointers is accomplished using Gray Code to avoid multi-bit signal transitions.
◦ Implemented 2 Flip-Flop Synchronizer to avoid meta-stability issues in CDC


***Reference*** - Simulation and Synthesis Techniques for Asynchronous FIFO Design ,Clifford E. Cummings, Sunburst Design, Inc. 
