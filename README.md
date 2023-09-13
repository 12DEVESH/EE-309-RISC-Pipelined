# EE-309-RISC-Pipelined
Microprocessor Course project 

*Please refer my other project named IITB-CPU for multicycle RISC processor \ 
*dspv is the main file and further details in report and datapath

problem statement:
Design a 6-stage pipelined processor, IITB-RISC-23, whose instruction set architecture is provided.  IITB-RISCis a 16-bit very simple computer developed for the teaching that is based on the Little Computer Architecture. The IITB-RISC-23 is a 16-bit computer system with 8 registers. It should follow the standard 6 stage pipelines (Instruction fetch, instruction decode, register read, execute, memory access, and write back). The architecture should be optimized for performance, i.e., should include hazard mitigation techniques. Hence, it should have implemented forwarding mechanism.  Implementation of branch predictor is optional.

IITB-RISC Instruction Set Architecture

IITB-RISC is a 16-bit very simple computer developed for the teaching that is based on the Little Computer Architecture. The IITB-RISC-23 is an 8-register, 16-bit computer system. It has 8 general-purpose registers (R0 to R7). Register R0 is always stores Program Counter. All addresses are byte addresses and instructions. Always it fetches two bytes for instruction and data. This architecture uses condition code register which has two flags Carry flag ( C ) and Zero flag (Z). The IITB-RISC-23 is very simple, but it is general enough to solve complex problems. The architecture allows predicated instruction execution and multiple load and store execution. There are three machine-code instruction formats (R, I, and J type) and a total of 14 instructions. They are illustrated in the figure below.

![image](https://github.com/12DEVESH/EE-309-RISC-Pipelined/assets/96682968/0e9d16db-9175-4af2-90ae-5c8827034ff8)

![image](https://github.com/12DEVESH/EE-309-RISC-Pipelined/assets/96682968/89d5a703-d4ea-4b75-98f2-406c8e14ff1b)

![image](https://github.com/12DEVESH/EE-309-RISC-Pipelined/assets/96682968/bcb3b747-6e8a-40e4-867a-f6eec5244d09)

![image](https://github.com/12DEVESH/EE-309-RISC-Pipelined/assets/96682968/cb8d6c92-7102-409d-aba0-0a36f35b6123)

![image](https://github.com/12DEVESH/EE-309-RISC-Pipelined/assets/96682968/16c1e2e7-d666-4427-9bf9-6b694198a955)

![image](https://github.com/12DEVESH/EE-309-RISC-Pipelined/assets/96682968/ed0a1d6a-f2c1-4243-9081-d546095f9fee)

![image](https://github.com/12DEVESH/EE-309-RISC-Pipelined/assets/96682968/b4fbff76-1add-4543-b78b-8441470c5bcd)








