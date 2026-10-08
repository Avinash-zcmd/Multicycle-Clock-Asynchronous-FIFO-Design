# Multicycle-Clock-Asynchronous-FIFO-Design
# Description:
A dual clock Asynchronous FIFO designed to safely transfer data across different clock domains using clock domain crossing (CDC) technique. 

# Problem Statement:
Data transfer between asynchronous clock domains often leads to data loss or metastability. This project addresses the need for a reliable, synchronized buffer that can handle variable burst rates without data corruption across multiple clock boundaries.

# My Work:
1. Architected and synthesized the dual clock FIFO in SystemVerilog with the depth of 16 and data width of 32bit.
2. Utilized Graycode pointers and 2-stage flip-flop synchronizers to manage CDC safely and mitigate the metastability .
3. Designed full/empty and almost full/empty flag logic.
4. Verified timing and executed multiple test cases to check burst rates and corner cases using a SystemVerilog testbench.

# Tools Used:
SystemVerilog, Synopsys DesignCompiler, Synopsys VCS, Verdi
