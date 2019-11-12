# About The Project

The picoProcessor (pP) is an 8-bit processor intended for educational purposes. It is similar to 8-bit microprocessors
for small embedded applications, but has an instruction set architecture more similar to RISC processors.
The pP has separate instruction and data memories. The instruction memory is 4K instructions in size, and the
data memory is 256 bytes. The pP can also address I/O devices using up to 256 input ports and 256 output ports.
Within the processor there are eight 8-bit general purposes registers, r0 to r7. R0 is always read as zero and ignores
writes. There is also a return-address stack of implementation-defined depth (at least four entries), an interrupt
return register and Zero (Z) and Carry (C) condition codes.

This pipeline processor consist from five stages and each stage has pipeline registers.
The stages:
1. IF: Instruction Fetch from instruction memory
2. ID: Instruction Decode, register read, and J/Br address
3. EX: Execute operation or calculate load/store address
4. MEM: Memory access for load and store
5. WB: Write Back result to register


**For more details about pP** 
<a href="pP-ISA.pdf">Click here </a><br>
**For my design details**
<a href="Designing for pipeline picoProcessor.pdf">Click here </a> <br>
**For the single-cycle design of pP**
<a href="https://github.com/AbdulrhmanSobhyAlsayed/DESIGN-SINGLE-CYCLE-PICOPROCESSOR.git">Click here </a> <br>
