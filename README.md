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
### Full Adder:
![Screenshot 2024-03-23 233917](https://github.com/Aadithya2201/FULL_ADDER_SUBTRACTOR/assets/145917810/68b6f7f5-1d76-46ec-a7ee-259a45cad994)

### Full Subtractor:
![Screenshot 2024-03-23 233945](https://github.com/Aadithya2201/FULL_ADDER_SUBTRACTOR/assets/145917810/5a3e012b-20ca-4b24-85b6-e29a45bcee6a)

**Procedure**
  STEP 1: Use module project name(input,output) to start the Verilog programmming.
  STEP 2: Assign inputs and outputs using the word input and output respectively. 
  STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression. 
  STEP 4: Use each output to represnt onre for differnce and the other for borrow. STEP 5: End the verilog program using keyword endmodule.

**Program:**
```
/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:
RegisterNumber:
*/
```
### Full Adder:
![316261256-cd0d7f70-36b8-4903-8267-e1eb9a876c38](https://github.com/Akshayaamt/FULL_ADDER_SUBTRACTOR/assets/144870472/fcd17dda-0694-4eb5-ad2d-a6185c03f6bb)

### Full Subtractor:
![316261261-db479dd9-112d-4960-8232-7f6b346ba105](https://github.com/Akshayaamt/FULL_ADDER_SUBTRACTOR/assets/144870472/6b860506-25e8-43ad-a980-60e63075e9a3)

**RTL Schematic**
### Full Adder:
![316261265-3c5aaf04-0768-4a9f-886b-110ed4ce86ff](https://github.com/Akshayaamt/FULL_ADDER_SUBTRACTOR/assets/144870472/fb1a5623-7100-46f8-a57e-2805af25b469)

### Full Subtractor:
![316261270-670554df-5e33-49dd-8508-6ea6eba01e18](https://github.com/Akshayaamt/FULL_ADDER_SUBTRACTOR/assets/144870472/3de313d4-352f-4806-9769-ca85e2fe23a6)

**Output Timing Waveform**
### Full Adder:
![316261271-af1e4b2f-fec6-4d3e-8d0f-80da2823b1fe](https://github.com/Akshayaamt/FULL_ADDER_SUBTRACTOR/assets/144870472/cee6b6b9-c8bf-48a3-8eb0-3aff5795b58c)

### Full Subtractor:
![Uploading 316261275-d1be3519-e4c0-4be9-96f5-686011180886.png…]()

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



