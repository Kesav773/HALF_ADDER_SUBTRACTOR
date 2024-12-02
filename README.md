# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

Half Adder

![Screenshot 2024-12-02 135317](https://github.com/user-attachments/assets/d5443434-8fe2-4d29-8944-75bbb990da1b)

Half subtractor

![Screenshot 2024-12-02 135336](https://github.com/user-attachments/assets/84469b00-1de2-44e4-bf91-93897cc31b10)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:ch.dinesh kumar RegisterNumber:*/24000305

![WhatsApp Image 2024-12-02 at 13 51 04_8e1264f0](https://github.com/user-attachments/assets/fb660f56-2828-4884-a595-095b8c1c0f33)

**RTL Schematic**
![WhatsApp Image 2024-12-02 at 13 51 28_ab6be8d3](https://github.com/user-attachments/assets/1c2fbc98-05d3-42c2-bd68-a6a2df90e571)

**Output/TIMING Waveform**
![WhatsApp Image 2024-12-02 at 13 50 16_ad008722](https://github.com/user-attachments/assets/f60a0a3b-af50-4f0e-b635-bf1c2cffe4f7)

**Result:** Thus the Half adder and Half Subtractor circuits are designed and the truth table is verified using Quartus software
# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

Half Adder

![Screenshot 2024-12-02 135317](https://github.com/user-attachments/assets/d5443434-8fe2-4d29-8944-75bbb990da1b)

Half subtractor

![Screenshot 2024-12-02 135336](https://github.com/user-attachments/assets/84469b00-1de2-44e4-bf91-93897cc31b10)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:ch.dinesh kumar RegisterNumber:*/24000305

![WhatsApp Image 2024-12-02 at 13 51 04_8e1264f0](https://github.com/user-attachments/assets/fb660f56-2828-4884-a595-095b8c1c0f33)

**RTL Schematic**
![WhatsApp Image 2024-12-02 at 13 51 28_ab6be8d3](https://github.com/user-attachments/assets/1c2fbc98-05d3-42c2-bd68-a6a2df90e571)

**Output/TIMING Waveform**
![WhatsApp Image 2024-12-02 at 13 50 16_ad008722](https://github.com/user-attachments/assets/f60a0a3b-af50-4f0e-b635-bf1c2cffe4f7)

**Result:** Thus the Half adder and Half Subtractor circuits are designed and the truth table is verified using Quartus software
# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

Half Adder

![Screenshot 2024-12-02 135317](https://github.com/user-attachments/assets/d5443434-8fe2-4d29-8944-75bbb990da1b)

Half subtractor

![Screenshot 2024-12-02 135336](https://github.com/user-attachments/assets/84469b00-1de2-44e4-bf91-93897cc31b10)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:KESAV.K.M RegisterNumber:*/24004978

![WhatsApp Image 2024-12-02 at 13 51 04_8e1264f0](https://github.com/user-attachments/assets/fb660f56-2828-4884-a595-095b8c1c0f33)

**RTL Schematic**
![WhatsApp Image 2024-12-02 at 13 51 28_ab6be8d3](https://github.com/user-attachments/assets/1c2fbc98-05d3-42c2-bd68-a6a2df90e571)

**Output/TIMING Waveform**
![WhatsApp Image 2024-12-02 at 13 50 16_ad008722](https://github.com/user-attachments/assets/f60a0a3b-af50-4f0e-b635-bf1c2cffe4f7)

**Result:** Thus the Half adder and Half Subtractor circuits are designed and the truth table is verified using Quartus software
