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

## Procedure :

1. Connect the supply (+5V) to the circuit.
2. Switch ON the main switch.
3. If the output is 1, then the led glows.

## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by : KEERTHIVASAN S

Register Number: 23002436

Code :

Half Subtractor :

![Exp4 hs code](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/dff9449a-4f6b-4380-9904-1f8b40b78573)

Full Subtractor :

![Exp4 fs code](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/cbedcc79-e5e8-4599-bbb0-85240daeb261)

Truthtable : 

Half Subtractor :

![Exp4 truthtable hs](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/e3dff7df-67cd-4cb6-ae72-1158e8c92ec1)

Full Subtractor :

![Exp4 truthtable fs](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/0e0b4371-937b-41ab-988e-0ff9b03b101b)

RTL Diagram :

Half Subtractor :

![Exp4 hs RTL diagram](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/2551f0be-e49a-4554-b220-5b1f57d0f6ca)

Full Subtractor :

![Exp4 fs RTL diagram](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/2639f1dc-ec8f-4aa7-8796-8fb5aca78c9f)

## Output :

Half Subtractor :

![Exp3 hs wave](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/d3d582d4-0196-4710-97b7-9b61bf70e9a4)

Full Subtractor :

![Exp3 fs wave](https://github.com/ikeerthivasanswaminathan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148937372/08c472fb-fb06-4dd7-8a8e-573b531701e4)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
