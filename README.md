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

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: PERARASU M
RegisterNumber:  22008454

Half adder program

module adder1(a,b,sum,carry);
input a,b;
output sum,carry;
xor(sum,a,b);
and(carry,a,b);
endmodule

Full adder program 

module adder1(a,b,sum,carry);
input a,b;
output sum,carry;
xor(sum,a,b);
and(carry,a,b);
endmodule

Logic symbol & Truthtable
RTL realization

### Output:
### RTL
Half adder
![Half adder](https://user-images.githubusercontent.com/118348589/210588055-d5328757-73f8-42c9-b82e-2ac375817926.jpg)

Full adder 
![Full adder](https://user-images.githubusercontent.com/118348589/210588332-f694322a-a47a-4054-9caa-602f61ae89ee.jpg)

### TIMING DIAGRAM
Half adder 
![Half adder td](https://user-images.githubusercontent.com/118348589/210589248-8847ca08-87f0-4b81-b890-70d6e5577279.jpg)

Full adder 
![Full adder td](https://user-images.githubusercontent.com/118348589/210589528-7d79da0e-1e5c-48f1-a3b5-e89aad050009.jpg)


### TRUTH TABLE 
Half adder 
![Half adder truth table](https://user-images.githubusercontent.com/118348589/210590465-2038b7d6-ad4c-4905-875b-44b641f60374.jpg)

Full adder 
![Full adder truth table ](https://user-images.githubusercontent.com/118348589/210590419-83d9b43c-8461-4425-b42c-7f301615368d.jpg)


### Result:
