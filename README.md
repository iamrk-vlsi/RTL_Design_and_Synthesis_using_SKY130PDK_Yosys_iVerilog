# RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog
This repo is to document the 5day "RTL Design and Synthesis using Verilog and Sky130 library" which was conducted by VLSI System Design Corp.

# Table of Contents
  * [ Introduction to Verilog RTL design and Synthesis](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/blob/main/README.md#Introduction-to-Verilog-RTL-design-and-Synthesis)
- [Timing libs hierarchical vs flat synthesis and efficient flop coding styles](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/blob/main/README.md#Timing-libs-hierarchical-vs-flat-synthesis-and-efficient-flop-coding-styles)
- [Combinational and sequential optmizations](#Combinational-and-sequential-optmizations)
- [GLS blocking vs non blocking and Synthesis Simulation mismatch](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/blob/main/README.md#GLS-blocking-vs-non-blocking-and-Synthesis-Simulation-mismatch) 
- [If, case, for loop and for generate](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/blob/main/README.md#Day-5)
- [Acknowledgements.](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/blob/main/README.md#Acknowledgements)

# Introduction to Verilog RTL design and Synthesis
- We were introducted to concepts of RTL design, Testbench.
- Setup of Sky130 libraries and related toolchain.
- iVerilog and GTKwave were used as Simulator and graphic waveform simulation tools, respectively.
- Labs were done , which can be found [here](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/tree/main/D1/Labs)
# Timing libs, hierarchical vs flat synthesis and efficient flop coding styles  
- We explored the library files of Sky130.
- Synthesis of an RTL in hierarchy as well as flattening was observed, using Yosys.
- Learnt about the importance of flip flop an its efficient coding styles in with sync and async set/resets.
- Labs were done , which can be found [here](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/tree/main/D2/Labs)
# Combinational and sequential optmizations
- learnt about optimization theory and optimization command opt_clean -purge for Yosys
- Combinational circuits and how to optimize them, some good examples of Mux.
- Sequential circuits, optimizations in dff, counters and some multiplier logics.
- Labs were done , which can be found [here](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/tree/main/D3/Labs)
# GLS, blocking vs non-blocking and Synthesis-Simulation mismatch
- Gate Level simulation and its significance.
- Blocking(used primarily for combinational logic) and Nonblocking statements(used primarily for sequential logic).
- Synthesis and Simulations mismatch in combinational logic, particularly in Muxes.
- Inferring of unwanted Latches during simulation due to improper sensitivity list,etc.
- Labs were done , which can be found [here](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/tree/main/D4/Labs)
# If, case, for loop and for generate
- Verilog constructs mentioned above were studied
- Caveats in If and case due to incomplete assignments were observed
- Importance of for loop for multiple evaluation and for generate for multiple instantiation.
- Labs were done , which can be found [here](https://github.com/iamrk-vlsi/RTL_Design_and_Synthesis_using_SKY130PDK_Yosys_iVerilog/tree/main/D5/Labs)
# Acknowledgements
- [Kunal Ghosh](https://github.com/kunalg123), Co-founder (VSD Corp. Pvt. Ltd)
- [Shon Taware](https://github.com/ShonTaware), Intern (Chipspirit)
