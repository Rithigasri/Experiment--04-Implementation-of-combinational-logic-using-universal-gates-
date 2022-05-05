# EXPERIMENT 04 IMPLEMENTATION OF COMBINATIONAL LOGIC USING UNIVERSAL GATES
## IMPLEMENTATION OF HALF SUBTRACTOR AND FULL SUBTRACTOR AND FULL SUBTRACTOR CIRCUIT
## AIM:
To implement the given logic function using NAND and NOR gates and to verify its operation in Quartus using Verilog programming.  
F=((C'.B.A)'(D'.C.A)'(C.B'.A)')' using NAND gate  
F=(((C.B'.A)+(D.C'.A)+(C.B'.A))')' using NOR gate  

## Equipments Required:
1. Hardware – PCs, Cyclone II , USB flasher
2. Software – Quartus prime
3. Theory
 
## PROCEDURE:



Write the detailed procedure here 


## Program:
/*
Program to design a Implementation of combinational logic using universal gates-  and verify its truth table in quartus using Verilog programming.
Developed by: Rithiga Sri.B
RegisterNumber:  212221230083


VERILOG PROGRAMMING USING NAND GATE:  
module universalgates(A,B,C,D,F);  
input A,B,C,D;  
output F;  
wire P,Q,R;  
assign P=C&~B&~A;  
assign Q=D&~C&~A;  
assign R=~C&B&~A;  
assign F=(~P&~Q&~R);  
endmodule
*/

## Output:

## Truthtable



##  RTL realization


## Timing diagram 

## Result:
 
