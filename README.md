## Developed by: Farhana H
## register number:212223230057
# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB
 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)


### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin
![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)
### Procedure
cc
## Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Farhana H
RegisterNumber:23012987
*/
## Code:
## Half adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/12e6be48-0b02-4128-a668-b487d45c09de)
## Full adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/13640a75-1dbd-45b9-be16-55832dbe3b59)
## Truth table:
## Half adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/067a9097-4ffa-45e3-a00d-e53d86fecbc3)
## Full adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/030b0e64-b0a9-473d-9d3e-ce462b78c2dd)
### Output:
## Half adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/cc8bfcc4-819b-4a6d-a116-4e05660eb7e0)
## Full adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/a4f70862-a50b-4603-9f69-9775955905a2)
### Result:
Thus the half adder and full adder circuits are designed and the truth tables is verified using quartus software
