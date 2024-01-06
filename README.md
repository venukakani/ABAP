# ABAP Practice Repository 

This repository contains a collection of ABAP programs that I have practiced.

## Programs

1. **Program 1:**
   
- Program Overview:
-This ABAP program, named ABAP_Prog1, performs basic arithmetic operations on three variables (x, y, and z).
-Variable Declaration:

-Three variables, x, y, and z, are declared using the DATA statement.
-Initialization:

-The program initializes the variable x with the value 10.
-Arithmetic Operation:

-Variable y is assigned the value 20.
-The program adds the values of x and y and stores the result in variable z.
-Display Result:

-The result of the addition (z) is displayed using the WRITE statement.
-Formatted Output:

-The program demonstrates different formatting options for displaying the result.
-The result is displayed left-justified using WRITE : / 'Addition of two numbers is', z LEFT-JUSTIFIED.
-The result is displayed centered using WRITE : / 'Addition of two numbers is', z CENTERED.
-This program essentially adds two numbers (x and y) and showcases different ways to present the result using the WRITE statement with formatting options.

2. **Program 2:**

- Program Overview:

The ABAP program ABAP_Prog2 allows users to perform basic arithmetic operations (addition, subtraction, multiplication, and division) based on user input through a selection screen.
Selection Screen Blocks:

The program has two selection screen blocks (BKL1 and BKL) to organize input parameters and radio buttons for arithmetic operations.
Input Parameters:

Two parameters, p_x and p_y, are declared for entering numeric values.
A radio button group (Grp1) allows the user to select the arithmetic operation.
Arithmetic Operations:

Depending on the selected radio button, the program performs addition, subtraction, multiplication, or division on the input values (p_x and p_y).
The result is stored in the variable V_Z.
Output Display:

The program uses the WRITE statement to display the result of the selected arithmetic operation.
Error Handling:

If none of the radio buttons is selected, an error message is displayed using the MESSAGE statement.
Initialization:

The INITIALIZATION event sets labels for input parameters and block titles.
Start-of-Selection Event:

The START-OF-SELECTION event processes the user's arithmetic operation selection and performs the corresponding calculation.
The program provides a simple user interface for performing arithmetic operations and handles user input using the selection screen.
