# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:NARMADHA S RegisterNumber:212223220065
## program
## module combinationalcircuit(A,B,C,D,F1);
## input A,B,C,D;
## output F1;
## wire x1,x2,x3,x4,x5;
## assign x1=(~A)&(~B)&(~C)&(~D);
## assign x2=(A)&(~C)&(~D);
## assign x3=(~B)&(C)&(~D);
## assign x4=(~A)&(B)&(C)&(D);
## assign x5=(B)&(~C)&(D);
## assign F1=x1|x2|x3|x4|x5;
## endmodule 


**RTL realization**



![Screenshot 2024-04-03 094321](https://github.com/narmadha2006/BOOLEAN_FUNCTION_MINIMIZATION/assets/151390280/dec6d9a4-73e7-4f91-a345-8a6d6cbef116)

**Truth table**


![Screenshot 2024-04-03 094429](https://github.com/narmadha2006/BOOLEAN_FUNCTION_MINIMIZATION/assets/151390280/bc2a50bc-bff6-46e4-8193-2aa42c9cff69)

**Timing diagram**


![Screenshot 2024-04-03 094516](https://github.com/narmadha2006/BOOLEAN_FUNCTION_MINIMIZATION/assets/151390280/45070c2f-ff00-4d80-b198-d779347109f3)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

