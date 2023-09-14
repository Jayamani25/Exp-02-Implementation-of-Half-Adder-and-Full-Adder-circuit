# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit
```
Developed by: Jayamani.R
RegisterNumber: 212222100014
```
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

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

#### Figure -01 HALF ADDER 

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -02 FULL ADDER 

![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)



## Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
## Program:
### Half Adder
```
module halfadder(A,B,sum,carry);
input A,B;
output sum,carry;
assign sum=A^B;
assign carry=A&B;
endmodule
```
### Full Adder
```
module fulladder(A,B,Cin,sum,carry);
input A,B,Cin;
output sum,carry;
assign sum=A^B^Cin;
assign carry=(A&B)|((A^B)&Cin);
endmodule
```



## Logic symbol & Truthtable
## Half Adder
![image](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/58797539-be40-4ef7-ac38-9dff4cf06fab)


## Full Adder
![image](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/a2714bef-7582-4c3c-952b-a5d32c1cf016)


### RTL realization
## Half Adder 
![halfadder_crop](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/7dee2363-fca8-4304-8389-c701099edb72)

## Full Adder
![fulladder_crop](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/9011d95b-9e9d-4dfa-9472-a25ad2a8d3c4)

## Output:
## Half Adder
![image](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/ed2f8027-68e9-4cb5-a358-a53411eb0b95)

## Full Adder
![image](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/5b9d0c9e-56db-4379-a202-64cb7f5cc501)

## Result:
Thus the half adder and full adder circuit are verified using its truth table in Quartus using Verilog programming.
