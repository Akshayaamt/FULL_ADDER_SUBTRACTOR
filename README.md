# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**
```
module ex4(a,b,c,sum,carry,BO,DIFF);
input a,b,c;
output sum,carry,BO,DIFF;
//Write syntax for full adder sum and carry in date flow modelling 
wire a0;
not (a0,a);
assign sum=a^b^c;
assign carry=(a&b)|(b&c)|(c&a);
//Write syntax for full subtractor Borrow and Difference in date flow modelling
assign DIFF=a^b^c;
assign Bbar=(~a&b)|(b&c)|(~a&c);
endmodule
```

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by:**AKSHAYAA M T**
RegisterNumber:**212223110002**
*/

**RTL Schematic**
![319864545-6f2b23ec-1c13-4697-89cb-670c4d8b57b7](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/144870472/7ba08872-cdbf-46b1-a9d4-564cda917548)
**Output Timing Waveform**

![319864573-8e5b103f-a3dc-45a0-9616-8a77ef17164f](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/144870472/3b91e0d1-650f-4cb4-b958-cee18925b50a)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



