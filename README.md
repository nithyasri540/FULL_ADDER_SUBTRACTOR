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

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7b13315f-d16e-4e8e-a50b-071ebaea1c4f" />

**RTL Schematic**
<img width="1920" height="1080" alt="Screenshot 2025-10-08 213346" src="https://github.com/user-attachments/assets/3e231d25-5924-41e8-8556-e8f452da4ef1" />
<img width="1920" height="1080" alt="Screenshot 2025-10-08 213806" src="https://github.com/user-attachments/assets/87c9280b-d0fa-4045-bd4d-39e7d8b4d92d" />


**Output Timing Waveform**
<img width="1920" height="1080" alt="Screenshot 2025-10-08 213521" src="https://github.com/user-attachments/assets/3bed325f-e6f0-4361-b25c-9d01885a5047" />
<img width="1920" height="1080" alt="Screenshot 2025-10-08 213939" src="https://github.com/user-attachments/assets/f751e5e4-fe07-4898-be55-6f4ffff9e04d" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



