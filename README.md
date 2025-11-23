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

full adder

<img width="832" height="220" alt="image" src="https://github.com/user-attachments/assets/3f0251ca-b986-4dcd-9521-62b366013b7c" />

full subtracter

<img width="671" height="226" alt="image" src="https://github.com/user-attachments/assets/22d6567c-74d5-4b15-872d-f3ad82ca969f" />


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by:devi.s RegisterNumber:25004804
*/

**RTL Schematic**

full adder
<img width="983" height="580" alt="image" src="https://github.com/user-attachments/assets/c7e60cd9-6127-4443-a896-e16f03d25747" />

full subtracter
<img width="1520" height="632" alt="image" src="https://github.com/user-attachments/assets/cabb7970-13eb-4bfc-979e-8dc9320e994a" />


**Output Timing Waveform**

full adder
<img width="1837" height="315" alt="image" src="https://github.com/user-attachments/assets/76adf2b9-3bad-4769-9fe4-170f820c4ba9" />

full subtracter
<img width="1280" height="191" alt="image" src="https://github.com/user-attachments/assets/068147be-ec33-40f3-9cdb-42742b17fd73" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



