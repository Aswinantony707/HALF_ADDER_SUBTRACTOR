## NAME:S.ASWIN ANTONY

## REG.NO:24001423

# EXPERIMENT-3:HALF ADDER AND SUBTRACTOR


## AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

## HALF ADDER:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

## HALF SUBTRACTIOR:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor


## PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## PROGRAM:

![Screenshot 2024-11-14 133059](https://github.com/user-attachments/assets/14776f91-be1f-4b0d-8439-1c69c3db9a7e)

## TRUTH TABLE:

![Screenshot 2024-11-14 135919](https://github.com/user-attachments/assets/b7032f70-d7c6-4a2f-8892-fc3eecf80fe2)

## RTL OUTPUT:

![Screenshot 2024-11-14 132930](https://github.com/user-attachments/assets/344237f3-5bc6-4f6a-80c2-dd10c5861c01)

## OUTPUTWAVEFORME:


![Screenshot 2024-11-14 144533](https://github.com/user-attachments/assets/902cb0bc-4dad-41ce-862e-3cb0eab9ede6)

## RESULT:

thus design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

