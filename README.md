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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:S.PRIYADHARSHINI
RegisterNumber:25017590
*/
<img width="1914" height="1020" alt="a1" src="https://github.com/user-attachments/assets/8e2bf839-3839-4262-ab62-e3b564dfdf55" />
<img width="1907" height="1021" alt="a2" src="https://github.com/user-attachments/assets/504815d0-8b83-4a90-a424-5af3ed93b38b" />

***output
<img width="1795" height="897" alt="b1" src="https://github.com/user-attachments/assets/654209f3-bf89-4590-a842-e52445de960c" />
<img width="1798" height="927" alt="b2" src="https://github.com/user-attachments/assets/37a884d5-9d3f-4dae-af30-7b57eb17a84a" />


**TIMING Waveform**
<img width="1919" height="1014" alt="c1" src="https://github.com/user-attachments/assets/4383ec56-a5d8-4069-b6b8-030966977bed" />
<img width="1912" height="1012" alt="c2" src="https://github.com/user-attachments/assets/a026a6fa-3cdb-451b-abe7-ef4f06c57c94" />


**Result:**
