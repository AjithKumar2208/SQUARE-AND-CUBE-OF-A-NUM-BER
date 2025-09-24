# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```

ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END


```

## OUTPUT

<img width="457" height="522" alt="image" src="https://github.com/user-attachments/assets/aa1db015-d92f-4124-b99e-7b3385a96f4b" />

<img width="452" height="340" alt="image" src="https://github.com/user-attachments/assets/f1603d4c-6542-48f0-86a2-f59b9d6c0a9b" />




## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```


ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END





```


## OUTPUT

<img width="461" height="515" alt="image" src="https://github.com/user-attachments/assets/e656875f-bdb7-4186-a862-4817ef73b733" />

<img width="479" height="369" alt="image" src="https://github.com/user-attachments/assets/909a2147-0e64-4536-b2c7-1085ad729cd3" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
