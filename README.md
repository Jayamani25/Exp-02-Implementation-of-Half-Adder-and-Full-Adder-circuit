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

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

#### Figure -01 HALF ADDER 

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -02 FULL ADDER 

![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)



### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### Program:

Developed by: Jayamani.R

RegisterNumber: 212222100014

### Logic symbol & Truthtable
## Half Adder
![image](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/58797539-be40-4ef7-ac38-9dff4cf06fab)

## Full Adder
![image](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/a2714bef-7582-4c3c-952b-a5d32c1cf016)


### RTL realization
## Half Adder 
![halfadder(3)](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/884ebd9a-89aa-4752-86a1-9ae4b520f02d)

## Full Adder
![fulladder (1)](https://github.com/Jayamani25/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/85949888/eb6af3e0-c780-4a0b-a6b4-1e1c8f23b438)

### Output:
## Half Adder


### Result:
