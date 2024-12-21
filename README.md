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

Developed by:Rauash.R
RegisterNumber:24001029

module logic_gates(a, b, c1, c2, c3, c4, c5, c6, c7);
    input a, b;
    output c1, c2, c3, c4, c5, c6, c7;
    assign c1 = ~a;
    assign c2 = a & b;
    assign c3 = a | b;
    assign c4 = ~(a & b);
    assign c5 = ~(a | b);
    assign c6 = a ^ b;
    assign c7 = ~(a ^ b);
endmodule



**RTL realization**
![image](https://github.com/user-attachments/assets/b07c03aa-e8d8-4df3-b9c4-74381007a7d5)

**Output:**
![image](https://github.com/user-attachments/assets/19525deb-6154-4057-99ca-aded101c7297)

**RTL**
![image](https://github.com/user-attachments/assets/80b523d4-f260-4774-863c-c3d744cda135)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

