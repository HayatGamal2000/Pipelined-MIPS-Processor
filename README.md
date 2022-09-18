# Pipelined-MIPS-Processor
The aim of this project is to design a 32-bit Pipelined processor for RISC (Reduced Instruction Set Computer) processor. 
The Pipelined processor was designed using MIPS ISA (Instruction Set Architecture) and divided into two parts: the datapath unit, and the control unit. 
The datapath unit divided into 5 parts: 
Fetch, Decode, Execute, Memory, Writeback. Verilog HDL language to design hardware modeling is used on Altera ModelSim tool. 
Then, it was tested to run Fibonacci number program.

The project consists of : 1-Datapath 2-Hazard Unit 4-Control Unit



we wrote thr RTL code of sub modules (level 1), then we integrate it in stages modules (level 2),then integrate the stages modules into datapath module(level 3) ,then we integrateddatapath ,control unit and hazard unit into TOP MODULE
![image](https://user-images.githubusercontent.com/71998574/190880726-67ca42be-fa02-4ebb-b130-19bcd6aa8df1.png)

simulation of programe 1: 
![Test1](https://user-images.githubusercontent.com/71998574/190880652-e16ce74c-8c15-447b-9276-0448b2802815.JPG)


simulation of programe 2: 
![Test2](https://user-images.githubusercontent.com/71998574/190880659-780d6fb0-061a-49f0-94a2-8042c13eafc2.JPG)


The RTL Viewer in Quartus of the MIPS Processor:
![PIPELINED RTL view](https://user-images.githubusercontent.com/71998574/190880666-6dfe67e1-24ed-4bf7-8eb1-f6959b0c8c87.PNG)
