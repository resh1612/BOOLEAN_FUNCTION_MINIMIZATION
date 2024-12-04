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

Developed by: RegisterNumber: 24900030

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

endmodul


**RTL realization**
![WhatsApp Image 2024-12-03 at 20 31 38_c3ecdfd0](https://github.com/user-attachments/assets/4409b678-7677-4c7a-a49d-6fc30f3d51b2)
![WhatsApp Image 2024-12-03 at 20 31 38_04250e9d](https://github.com/user-attachments/assets/f4d8bdf7-3591-4b44-b418-87ba1ff6fae8)


**Truth Table**
![WhatsApp Image 2024-12-03 at 20 31 39_ac7893ee](https://github.com/user-attachments/assets/2593e966-20dc-421f-a4e6-fbd3b45c070a)
![WhatsApp Image 2024-12-03 at 20 31 39_18f28ad3](https://github.com/user-attachments/assets/fa612a2e-108b-4b04-af67-77aebe670b2d)


**Output:**
![WhatsApp Image 2024-12-03 at 20 31 39_17bf5910](https://github.com/user-attachments/assets/4ceda84e-3a2f-42a3-b378-a6432376f2b4)
![WhatsApp Image 2024-12-03 at 20 31 39_297f0607](https://github.com/user-attachments/assets/f1430436-83ce-43bd-9769-79240842564b)



**RTL**

**Timing Diagram**
![WhatsApp Image 2024-12-03 at 20 31 39_7098a31f](https://github.com/user-attachments/assets/6701bb32-ceac-44ea-8f96-c63a32a9f0b2)
![WhatsApp Image 2024-12-03 at 20 31 39_29789a31](https://github.com/user-attachments/assets/fb1cc9b7-f2d1-4932-9ca1-722a97eac893)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

