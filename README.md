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
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable

HALF ADDER
![212870671-22def116-4573-4ebe-b055-c0db72c05f55](https://user-images.githubusercontent.com/119475762/214545216-a5c890c6-8600-4e58-8b92-68f456cc6b4e.png)

FULL ADDER
![212871394-45d369db-b012-40d4-b8e7-3f4016c91324](https://user-images.githubusercontent.com/119475762/214545473-28b18a90-b480-46f4-8f39-060a67316b5f.png)

RTL realization
HALF ADDER
![212871692-6e97dd93-618d-4f6f-8b56-541f76c4c2ce](https://user-images.githubusercontent.com/119475762/214545708-85fb4ba2-d5b3-41e6-b398-a9a51726c705.png)
 
FULL ADDER
![212871937-a21d1f9d-cddf-46d4-9e90-bfe498712f98](https://user-images.githubusercontent.com/119475762/214545807-a0f8def6-83e5-48b3-88b3-1d80075fee2f.png)

### TIMING DIAGRAM
HALF ADDER
![212872254-ba36b6fb-ed69-479c-aa50-2bde5280c1cc](https://user-images.githubusercontent.com/119475762/214545967-27f61388-8117-4789-8154-da6e974d40a6.png)

FULL ADDER
![212872557-600dea36-5664-4f00-be96-4caf59c4217a](https://user-images.githubusercontent.com/119475762/214546141-9204e927-bee6-488e-bbee-28bfdf25de4e.png)

### TRUTH TABLE 
![212872890-ee84e3eb-728d-49cb-b114-fd25562f6f7b](https://user-images.githubusercontent.com/119475762/214546211-0f509942-e43e-4e0d-8f2d-5be889137baa.png)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming
