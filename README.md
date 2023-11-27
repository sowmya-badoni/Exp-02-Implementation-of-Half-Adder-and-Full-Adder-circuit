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

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: SOWMYA BADONI
RegisterNumber:  23001999

## CODE:
## HALF ADDER:
![Exp3 ha code](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/0047fff0-5c31-4361-a083-cd8f73ae3e8b)

## FULL ADDER:
![Exp3 fa code](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/f171718d-b6e2-4311-a723-2e92d4408acb)

## TRUTH TABLE:
## HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/9fd3ab5b-2b1f-490a-8884-b227f4bc0ed5)

## FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/50a99a21-8823-43d0-88df-1b56ba158da8)

### Output:
### RTL:
## HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/aefdef3b-ff25-4e97-8cb2-6ebcacdf7115)

## FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/1b75d24e-6d90-42a3-a768-6cc305213541)

## TIMING DIAGRAM:
### HALF ADDER:
![exp3 ha wave](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/97ea9499-81f4-41e6-b0c4-a624d82dd79e)
### FULL ADDER:

![Exp3 fa RTL diagram](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/798c0c60-cd2e-471c-b33e-00912b925939)

## TRUTH TABLE :
### HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/706d221e-8a90-41c3-9485-f1680125f5a8)

### FULL ADDRER:
![Exp3 truthtable (fa)](https://github.com/sowmya-badoni/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152136324/fbdda3a8-9345-41a6-a66e-a79972e4f077)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming
