EX-21-POINTERS
# AIM:
Write a C program to convert a 23.65 into 25 using pointer

## ALGORITHM:
1.	Declare a double variable to hold the floating-point number (23.65).
2.	Declare a pointer to double to point to the address of the variable.
3.	Use the pointer to modify the value to 25.0.
4.	Print the modified value.

## PROGRAM:
![Screenshot 2025-04-26 102637](https://github.com/user-attachments/assets/c615d777-8572-41f5-a2dd-f7d2af43f10a)

## OUTPUT:
![Screenshot 2025-04-26 102641](https://github.com/user-attachments/assets/a94f278f-bcfe-4e5c-a919-12ddda197c52)












## RESULT:
Thus the program to convert a 23.65 into 25 using pointer has been executed successfully.
 
 


# EX-22-FUNCTIONS AND STORAGE CLASS

## AIM:

Write a C program to calculate the Product of first 12 natural numbers using Recursion

## ALGORITHM:

1.	Define a recursive function calculateProduct that takes an integer parameter n.
2.	Return n multiplied by the result of the calculateProduct function called with n - 1.
3.	Declare an integer variable n and an unsigned long long variable product.
4.	Initialize n with the value 12 (for the first 12 natural numbers).
5.	Call the calculateProduct function with n and store the result in the product variable.
6.	Print the result, indicating it is the product of the first 12 natural numbers.

## PROGRAM:
![Screenshot 2025-04-26 103004](https://github.com/user-attachments/assets/d88a2f25-4f18-4982-b2f5-060e1c6cc988)


## OUTPUT:
![Screenshot 2025-04-26 103021](https://github.com/user-attachments/assets/0ef81504-6dec-43aa-8924-b801ec14db4e)
         		
## RESULT:

Thus the program has been executed successfully.
 
 


# EX-23-ARRAYS AND ITS OPERATIONS

## AIM:

Write C Program to find Sum of each row of a Matrix

## ALGORITHM:

1.	Declare and initialize the matrix with the desired values.
2.	Create a loop to iterate through each row of the matrix.
3.	Inside the loop, calculate the sum of the elements in each row.
4.	Print the sum for each row.

## PROGRAM:
![Screenshot 2025-04-26 103508](https://github.com/user-attachments/assets/574b14a1-e480-4e1a-a7d4-6948c6cfaf43)



## OUTPUT
![Screenshot 2025-04-26 103512](https://github.com/user-attachments/assets/1407a11a-79ab-470d-91e2-48627489cd3e)


 
 

 ## RESULT
 Thus the program has been executed successfully.
 


# EX-24-STRINGS

## AIM:

Write C program for the below pyramid string pattern. Enter a string: PROGRAM Enter number of rows: 5 P R O G R A M P R O G R A M P R O G R A M

## ALGORITHM:

1.	Input the number of rows for the pyramid (e.g., num_rows).
2.	Initialize variables:i for the row count (starting from 1),j for the character count (starting from 1)
3.	Start a loop for i from 1 to num_rows (for each row of the pyramid).
4.	Calculate the midpoint position as midpoint = (2 * num_rows - 1) / 2.
5.	End the program.

## PROGRAM:

![Screenshot 2025-04-26 104208](https://github.com/user-attachments/assets/cbb00dc7-bcdf-497e-841a-37ef0103eb66)

 ## OUTPUT
![Screenshot 2025-04-26 104211](https://github.com/user-attachments/assets/eb57f7b7-320f-40ab-a7fe-02edfd02d527)

 

## RESULT

Thus the C program to String process executed successfully
 

# EX -25 –DISPLAYING ARRAYS USING POINTERS
## AIM

Write a c program to read and display an array of any 6 integer elements using pointer

## ALGORITHM
Step 1: Start the program.
Step 2: Declare the following:
•	Integer variable i for iteration.
•	Integer variable n to store the number of elements.
•	Integer array arr[10] to hold up to 10 elements.
•	Integer pointer parr and initialize it to point to the array arr.
Step 3: Read the value of n (number of elements) from the user.
Step 4: Loop from i = 0 to i < n:
•	Read an integer value and store it in the address parr + i using pointer arithmetic.
Step 5: Loop from i = 0 to i < n:
•	Print the element at *(parr + i) using pointer dereferencing.
Step 6: End the program.

## PROGRAM
![Screenshot 2025-04-26 104704](https://github.com/user-attachments/assets/b3f5aa2d-54a9-4865-b210-f2bd96293094)


## OUTPUT

![Screenshot 2025-04-26 104707](https://github.com/user-attachments/assets/43172c37-fbbe-43c6-8b1a-c6d95b323c59)

## RESULT

Thus the C program to String process executed successfully
