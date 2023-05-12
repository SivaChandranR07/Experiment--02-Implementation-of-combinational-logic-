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
```
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: Sva Chandran R
RegisterNumber:  212222240099
*/
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

![img1](https://github.com/SivaChandranR07/Experiment--02-Implementation-of-combinational-logic-/assets/113497395/86507832-7475-46e8-a023-92899bf4bbd1)

![img2](https://github.com/SivaChandranR07/Experiment--02-Implementation-of-combinational-logic-/assets/113497395/9de1f313-b8bd-4373-9125-753aee718811)
 


## Timing Diagram
![img3](https://github.com/SivaChandranR07/Experiment--02-Implementation-of-combinational-logic-/assets/113497395/aca0c16c-5aef-47e0-b2ad-9fe7b25119d2)
![img4](https://github.com/SivaChandranR07/Experiment--02-Implementation-of-combinational-logic-/assets/113497395/e4215639-e472-42a5-b0e3-56ea8c8a444d)


## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
