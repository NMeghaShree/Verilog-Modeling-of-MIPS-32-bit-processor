# Verilog-Modeling-of-MIPS-32-bit-processor
Verilog implementation of MIPS32 Pipeline using 32 32-bit GPRs and some addressing modes. It is word addressable (we assume memory word size is 32 bits).  

Test bench 1 performs addition operation and writes values into registers as following:-  
R1=10+0=10  
R2=20+0=20  
R3=25+0=25  
R4=R1+R2=30  
R5=R4+R3=55  
Test bench 2 loads a word stored in memory location 120, adds 45 to it and stores the result in memory location 121.  
The result obtained:-  
Mem[120]=85 // value at memory 120  
Mem[121]=130 //85+45=130  
The waveforms of clocks and registers obtained:-  
![tb1](https://github.com/NMeghaShree/Verilog-Modeling-of-MIPS-32-bit-processor/assets/98016085/c853b578-462d-4734-92d4-5062d762cb8d)
