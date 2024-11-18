# NAME : SHREYESHKAR SEKAR
# REFERENCE NUMBER : 24900622

# EXP 4 : FULL_ADDER_SUBTRACTOR

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

**FULL ADDER**
![image](https://github.com/user-attachments/assets/cf1a163f-d341-4b09-bfa5-dd05387525ee)

**FULL SUBTRACTOR**
![image](https://github.com/user-attachments/assets/36e82dc3-7fc7-4f57-a016-5f1a221b5e29)


**Procedure**

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram 

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber: 24900622
*/
**FULL ADDER**

![FULL ADDER CODE](https://github.com/user-attachments/assets/50ccb85a-5efd-482a-8592-f179be2c6ced)

**FULL SUBTRACTOR**

![WhatsApp Image 2024-11-17 at 8 44 14 PM](https://github.com/user-attachments/assets/e2cd3b24-05e5-463c-a3c9-9579e7afe73d)



**RTL Schematic**


**FULL ADDER**

![FULL ADDER DIA](https://github.com/user-attachments/assets/190ca39d-92bf-45de-83bb-eb717a63c214)


**FULL SUBTRACTOR**

![WhatsApp Image 2024-11-17 at 8 36 15 PM](https://github.com/user-attachments/assets/3e179ddc-23db-460a-aeb9-97f42cafb27e)



**Output Timing Waveform**

**FULL ADDER**

![FULL ADDER OUTPUT](https://github.com/user-attachments/assets/ee597ec4-7a30-41c9-816e-6c9e207be09a)


**FULL SUBTRACTOR**

![WhatsApp Image 2024-11-17 at 8 43 19 PM](https://github.com/user-attachments/assets/dc395b03-f614-4f76-b9d7-b3c8ff8e96fa)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



