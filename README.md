HALF_ADDER_SUBTRACTOR
Implementation-of-Half-Adder-and-Half Subtractor-circuit

AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![bsv](https://github.com/Munimadhuriganji/HALF_ADDER_SUBTRACTOR/assets/138849444/75492474-c782-4f42-9418-9483e6e72ab7)

Figure -01 HALF ADDER

Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.

Diff = A’B+AB’ =A ⊕ B Borrow = A’B

![svsv](https://github.com/Munimadhuriganji/HALF_ADDER_SUBTRACTOR/assets/138849444/c6e116e1-0385-4282-885d-aad8ceae114e)

Figure -02 HALF Subtractor

Truthtable

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

Program: Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: SHIVRAJ R

RegisterNumber: 212223110051

RTL Schematic

![exp_33-1](https://github.com/Munimadhuriganji/HALF_ADDER_SUBTRACTOR/assets/138849444/abfd5a98-52e0-4aae-a445-e142d27cdea0)
![gvg](https://github.com/Munimadhuriganji/HALF_ADDER_SUBTRACTOR/assets/138849444/70596fc4-084d-4296-8aef-11b0fe55cd92)

Result:

Hence the output was verified successfully
