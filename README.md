## Developed by: Farhana H
## register number:212223230057
# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

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
Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
## Program:
```
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Farhana H
RegisterNumber:212223230057
module half_adder(A,B,C,S);
input A,B;
output S,C;
assign c=A&B;
assign S=A^B;
endmodule


module FullAdder(a,b,carryin,sum,carryout);
input a,b,carryin;
output sum,carryout;
wire x,p,q,r;
xor(x,b,carryin);
xor(sum,x,a);
and(p,a,b);
and(q,b,carryin);
and(r,a,carryin);
or(carryout,p,q,r);
endmodule
```
*/

## Truth table:
## Half adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/9d691985-89db-4235-9362-318a7613d6d8)

## Full adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/52d4361f-2698-43c0-9510-c1c94505f031)

### RLT realization
## Half adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/42ab55b3-4d9b-4b23-bb54-437d9df68070)
## Full adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/ad02879a-d046-4eb7-aa96-586225cbd119)

## output
## Timing diagram
## Half adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/12c4b84f-ee53-44bc-aac9-cc2a0f208655)
## Full adder
![image](https://github.com/syedfayaz3105/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147144126/7136a7d3-7ed9-44c8-ab04-eceeadcbf58e)



### Result:
Thus the half adder and full adder circuits are designed and the truth tables is verified using quartus software
