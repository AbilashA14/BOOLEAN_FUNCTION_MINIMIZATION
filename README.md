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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
   Developed by:ABILASH A
   RegisterNumber:24000105
*/
```
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```


**RTL realization**

![Screenshot 2024-12-03 225129](https://github.com/user-attachments/assets/e16db864-10d4-48d2-afef-b04b6be27faf)



**Output:**


![Screenshot 2024-12-03 225158](https://github.com/user-attachments/assets/92f98caa-fc83-4a04-995e-31e7a275b8f4)


**RTL & Timing Diagram**

![Screenshot 2024-12-03 225222](https://github.com/user-attachments/assets/29ebcb12-5608-4e20-a6d7-0c2448f01bc6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

