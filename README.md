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
1. Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

designed by :BARATH V

reg no:25008324


**Program:**


FULL ADDER

<img width="606" height="321" alt="image" src="https://github.com/user-attachments/assets/7303dd23-866c-4a8d-afd3-042152d98256" />

FUL SUBTRACTOR

<img width="702" height="303" alt="image" src="https://github.com/user-attachments/assets/c77ebd91-db00-4887-81e0-efd79913bdde" />

**RTL Schematic**
FULL ADDER
<img width="1920" height="1080" alt="Screenshot (73)" src="https://github.com/user-attachments/assets/a8e88bee-1527-4a8a-999f-be96a5b57a1b" />
FUL SUBSTRACTOR
<img width="1920" height="1080" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/0684f33d-e298-404d-a6e5-06b8d8e28a1d" />


**Output Timing Waveform**
FULL ADDER
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f1c5c487-9388-4250-b521-f3d35cb4a7f8" />
FULL SUBSTRACTOR
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e00e2162-532e-4801-a29c-01ab80ecbd13" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



