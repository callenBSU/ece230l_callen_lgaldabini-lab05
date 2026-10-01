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
Connor Allen & Logan Galdabini
## Lab Summary
In this lab, we first learned the syntax of verilog and how to make our scripts.
We then made the boolean functions for the truth tables using KMaps. After, we
created our top.v and uncommented the needed ports in constraints.xdc. We then 
generated the bitstream and confirmed that our logic equations worked by going
through the truth tables/
## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file contains the implementation of the connection for both circuits.
The basic structure is that the main models declares each input and output for all
circuits/LEDs.
### 2 - Explain the function of the Constraints file.
The function of a constraint file is to enable or disable the ports you will be 
using during a lab. These ports include LEDS, switches, a segment display, etc.
Ports will not work if you do not enable them beforehand.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
I think that for the second truth table, using minterms was the appropriate choice
since it condensed the equation. For the first truth table, minterms should have been 
used. There was a square of ones that we could have used that would have simplified
everything.