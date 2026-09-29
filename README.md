# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Christopher Smith &
Trace Hughey

## Lab Summary
We learned the basics of Verilog modules and how to wire them up together.  We learned about constraint files and how they allow Vivado to convert our designs to actual hardware. We learned how to view the physical FPGA on our selected OBUF that represents the silicon on the board.

## Lab Questions

### 1 - Explain the role of the Top Level file.
This is used on the top level to hook together all of our ciruits/switches/outputs, etc.  Even though Verilog is not procedural, top can be thought of as the main entry point to the verilog module. 

### 2 - Explain the function of the Constraints file.
The constraints file allows the synthesizer to assign our design to the actual hardware pins that the constraints correspond to on specific boards.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
No for A and indifferent for B. We would've chosen to do Minterms (SOP) for circuit A because there were only 4 1s and they were all in 1 group, so it would be simpler.  For circuit B we think both are equally efficient, but we like SOP more, so we still would've chosen Minterms.  
