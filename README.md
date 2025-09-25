# Lab 05 - Combinatorial Logic
Gage Munt

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

## Lab Questions

### 1 - Explain the role of the Top Level file.

 The top level file acts as the driver class in any other programming language. Its what connects our sub circuits (`circuit_A` and `circuit_B`) together in logic. 

### 2 - Explain the function of the Constraints file.

 The function of the constraints file is to map our digital/programmed inputs and outputs to real pins on the FPGA or real world board. 

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?

 Our selection was correct for the Minterm and Maxterms, however for circuit_A we would have chosen the Minterm because the solution is much simpler. SOP: `~A * D` vs POS: `~A * (C + D) * (~C + D)`. 
 Both SOP and POS had the same length output for circuit_B.

