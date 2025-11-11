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
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END

```

## OUTPUT
<img width="1337" height="582" alt="494699214-430ee2c4-698a-45b1-881c-bfa094ab004a" src="https://github.com/user-attachments/assets/2c14f62e-cee3-48e9-9f31-61db15149e7f" />

# MANUAL
![WhatsApp Image 2025-11-11 at 20 02 04_cbb55dd8](https://github.com/user-attachments/assets/81d327e7-62af-4a65-8e22-7dc1ac96784d)


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
<img width="1386" height="779" alt="494699248-355fd01a-36c1-458e-a9ff-a9d1d1859b7c" src="https://github.com/user-attachments/assets/b4e21a25-a209-4494-b703-f7bb0bb42611" />

# MANUAL
![WhatsApp Image 2025-11-11 at 20 02 15_65aeb402](https://github.com/user-attachments/assets/3e532ae3-ad60-4636-a88e-a7cf5010780d)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
