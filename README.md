# Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-
## AIM:
To study about the different digital IC’s and to verify the truth table in Quartus for the basic logic gates using Verilog programming.

## EQUIPMENTS REQUIRED:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
## INTRODUCTION
Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate

OR gate

NOT gate

NAND gate

NOR gate

Ex-OR gate

Ex-NOR gate

### 1) AND gate
The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high.

A dot (.) is used to show the AND operation i.e. A.B or can be written as AB

Y= A.B

### 2) OR gate
The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high.

A plus (+) is used to show the OR operation.

Y= A+B

### 3) NOT gate
The NOT gate is an electronic circuit that produces an inverted version of the input at its output. 

It is also known as an inverter.

If the input variable is A, the inverted output is known as NOT A.

This is also shown as A' or A with a bar over the top, as shown at the outputs.

Y= A'

### 4) NAND gate
This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. 

The outputs of all NAND gates are high if any of the inputs are low.

The symbol is an AND gate with a small circle on the output.

The small circle represents inversion.

Y= (AB)’

### 5) NOR gate
This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. 

The outputs of all NOR gates are low if any of the inputs are high. 

The symbol is an OR gate with a small circle on the output. The small circle represents inversion.

Y= (A+B)’

### 6) Ex-OR gate
The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high.

An encircled plus sign (⊕) is used to show the Ex-OR operation.

Y= A⊕B

### 7) Ex-NOR gate
The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate.

It will give a low output if either, but not both of its two inputs are high.

The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.

Y= A⊕B

## PROCEDURE

Connect the supply (+5V) to the circuit

Switch ON the main switch

Press the switches for inputs “A” and “B”. The switch is ON state when 1 is pressed. The switch is OFF state when 0 is pressed.

If the output is 1, then the bulb glows.

Check all the gates following the same procedure.

## PROGRAM:

Program to verify the truth table in quartus for the basic logic gates using Verilog programming.

Developed by: SUJITHRA B K N

RegisterNumber:  212222230153

```
module ex01(a,b,yand,yor,ynot,yxor,ynand,ynor,yxnor);
input a,b;
output yand,yor,ynot,yxor,ynand,ynor,yxnor;
and(yand,a,b);
or(yor,a,b);
not(ynot,a);
xor(yxor,a,b);
nand(ynand,a,b);
nor(ynor,a,b);
xnor(yxnor,a,b);
endmodule

```


## OUTPUT:


### Logic symbol & Truthtable

![deex012](https://github.com/sujithrabkn/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/119477857/b27653b4-925b-4ec2-bcbb-3a3431046b7f)

![Screenshot 2023-09-02 185605](https://github.com/sujithrabkn/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/119477857/06d7dcc4-8bb0-4ce2-a3bf-76941ff7bc32)

![Screenshot 2023-09-02 185613](https://github.com/sujithrabkn/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/119477857/f5b03a51-695b-4a5b-a6c5-e009608bccf8)


### RTL realization

![deex01](https://github.com/sujithrabkn/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/119477857/5c96eb86-785a-4456-a510-e8f6555017c1)


## RESULT:
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.
