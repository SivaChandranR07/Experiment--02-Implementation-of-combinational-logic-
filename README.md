# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
```
module toexpoto(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=(~b&~d)|(~a&b&d)|(a&b&~c);
endmodule

module toexpo(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=(x&y)|(w&y)|(~y&z);
endmodule
```
## RTL realization

## Output:
## RTL
## Timing Diagram
## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
