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

First program:
module EXP2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d|a&b&~c|~a&b&d));
endmodule

Second program:
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z|x&y|w&y));
endmodule

Developed by: Gokul Nath R 
RegisterNumber:212224230077


**RTL realization**
![436171792-e38539ad-c95d-4d9b-b71a-8b56d53d6706](https://github.com/user-attachments/assets/101ea2d7-b8cc-4ffb-a155-0b2ea27e0d9f)
![436171867-36c2227c-0bbd-436c-940f-6b648f2023d8](https://github.com/user-attachments/assets/d1a7fc76-79ac-4f82-91e4-428186056371)

**Output:**

**RTL**
![436138106-a5932a20-a600-42ae-b20f-1372db585113](https://github.com/user-attachments/assets/a7b94d96-f626-4e5c-baac-d87d6863529d)
![436140973-7cd3dc12-37a9-454b-aafe-abb678604d72](https://github.com/user-attachments/assets/4cd8659c-8920-46e9-a991-f0e9d0e33a9d)

**Timing Diagram**
![436135325-91f40222-e8d2-432a-a6bd-039ddb523fff](https://github.com/user-attachments/assets/80276e13-db12-4dbf-adb9-7dddae8118ff)
![436144628-ed7b78f8-f477-45a1-84c6-65074c7c3bec](https://github.com/user-attachments/assets/56b09794-de98-4bef-a6cd-f07d3266ee69)
**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

