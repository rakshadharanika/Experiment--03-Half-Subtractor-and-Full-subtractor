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
Developed by: V RAKSHA DHARANIKA
RegisterNumber:  23013260



###CODE:



HALF SUBTRACTOR:


![Exp4 hs code](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/0bbca9ef-e791-4bdc-9c95-0f5c42080a9a)




FULL SUBTRACTOR:


![Exp4 fs code](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/81cb63a7-e6b9-4a4a-84f0-9de13c026ab3)




## Output:

## Truthtable:



HALF SUBTRACTOR:

![Exp4 truthtable hs](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/cf2977c3-e1e0-4f0c-bb78-3354672e5f29)






FULL SUBTRACTOR:



![Exp4 truthtable fs](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/1e82ad30-477d-406d-88a1-795a50c51fcd)



##  RTL :
HALF SUBTRACTOR:


![Exp4 hs RTL diagram](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/7a07d859-b19e-4967-ba0b-1f7bcb22929a)




FULL SUBTRACTOR:
![Exp4 fs RTL diagram](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/4906ce1f-1432-43f7-8f1e-77e099a78735)





## Timing diagram :




HALF SUBTRACTOR:


![hs wave](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/82410179-f05f-455e-bb36-64f3d9e41280)




FULL SUBTRACTOR:

![fs wave](https://github.com/rakshadharanika/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149348380/1a2d26b8-ece2-4523-9248-211720c47f26)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
