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

<img width="832" height="220" alt="image" src="https://github.com/user-attachments/assets/e0e4f999-8682-4a6b-ae88-0a544363deef" />
<img width="671" height="226" alt="image" src="https://github.com/user-attachments/assets/5e05fcd0-27d5-40fd-951e-c3f4e39bb08e" />


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:devi.s RegisterNumber:25004804
*/


**RTL Schematic**

full adder
<img width="983" height="580" alt="image" src="https://github.com/user-attachments/assets/bbf67bc2-0a2c-4a82-a0ee-70eb746ccb16" />

 full subtracter
 <img width="1520" height="632" alt="image" src="https://github.com/user-attachments/assets/b645c12f-6304-41d2-9f30-7c927e42c428" />

**Output Timing Waveform**

full adder
<img width="1837" height="315" alt="image" src="https://github.com/user-attachments/assets/7d5b0e0b-eff9-4ae0-a933-e66e070abbae" />

full subtracter
<img width="1280" height="191" alt="image" src="https://github.com/user-attachments/assets/45c0cb6d-251e-41d3-a324-3da4ce4dbbe4" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



