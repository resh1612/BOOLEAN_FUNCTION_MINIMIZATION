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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber : 24900030


i)
module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule



ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y&z)|( w &y )|(x & y));

endmodule


**RTL realization**
![WhatsApp Image 2024-12-03 at 20 31 37_e3565a06](https://github.com/user-attachments/assets/f387a767-bb1e-46a3-9f26-f852140bae6d)
![WhatsApp Image 2024-12-03 at 20 31 37_94e5768a](https://github.com/user-attachments/assets/27f15794-6355-4c8e-af73-2d48c9fde2cd)


**Output:**
![WhatsApp Image 2024-12-03 at 20 31 38_632bf8ef](https://github.com/user-attachments/assets/640693e6-f069-43e9-a71e-445a3fcc6c75)
![WhatsApp Image 2024-12-03 at 20 31 38_c96e80a7](https://github.com/user-attachments/assets/6fa307bd-8d80-41db-8d40-381e6b396125)


**RTL**

**Timing Diagram**
![WhatsApp Image 2024-12-03 at 20 31 38_e4e0a9f6](https://github.com/user-attachments/assets/1a44439a-e884-45b7-8bc2-8dafebfb94bc)
![WhatsApp Image 2024-12-03 at 20 31 38_62f82803](https://github.com/user-attachments/assets/62aaea31-c005-4da1-9a8c-b64b372cf081)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

