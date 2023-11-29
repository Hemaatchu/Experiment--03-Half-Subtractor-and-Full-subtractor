# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.


Developed by: Hemavathy.S
RegisterNumber: 23013552 



## Code: 
![exp 4 half sub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/f701d982-8ad6-4b69-a01a-0eae610266d0)
![exp 4 fullsub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/2692913b-1c5b-4e13-8f70-3f5e0b37c399)


## Truthtable
![exp 4 half sub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/5d936674-a8e4-4a6e-ba8d-4e4a4d4740ad)

![exp 4 fullsub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/8659e33f-247e-4291-897f-ffbea528b6f6)



## Output RTL realization
![exp4halfsub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/2735e144-48c1-43eb-896d-ad79b925f205)

![exp4fullsub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/41071d8a-f790-451e-9c1c-188eed444509)


## Timing diagram 
![halfsub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/399e292c-87ed-4407-aa7e-e45faaf4779d)

![fullsub](https://github.com/Hemaatchu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147328300/0b57ab5b-47d1-49d9-891c-7554cd7819d7)



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
