# Five_Stage_Pipelining_RISCV

This project implements a Five-Stage Pipelining in RISC-V using a pipelined RISC-V processor with the standard five-stage pipeline:<br>

•	Instruction Fetch – Fetches the instruction from memory.<br>
•	Instruction Decode – Decodes the instruction and reads registers.<br>
•	Instruction Execution – Performs arithmetic or logical operations.<br>
•	Memory Access – Reads from or writes to memory.<br>
•	Write-Back – Writes results back to the register file.<br>


•	**Definition of Pipelining:**<br>
Pipelining is a technique used in computer architecture to enhance the execution speed of instructions by overlapping multiple instruction stages. Instead of executing one instruction at a time, pipelining divides instruction execution into multiple stages, allowing multiple instructions to be processed simultaneously in different stages of execution.

![Timing Diagram](https://github.com/user-attachments/assets/67e9ae37-87b2-4b25-8cfd-48f582798fd0)

**Pipelined Processor:**
![Pipelined Processor](https://github.com/user-attachments/assets/21eefcb6-04f9-43e4-9579-836170424464)

**Elaboration Design using VIVADO:**![schematic](https://github.com/user-attachments/assets/5cbd8f5a-7513-4d66-9968-72acb55a75fb)
![image](https://github.com/user-attachments/assets/e6d78d0c-805b-4dd3-8682-67198b57ac9d)
