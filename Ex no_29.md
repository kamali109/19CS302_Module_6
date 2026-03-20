# EX 29 C program to create two float variables using calloc() and find minimum among them.

## AIM:
To write a C program to create two float variables using calloc() and find minimum among them.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
C program to create two float variables using calloc() and find minimum among them.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *num1, *num2, minimum;
 num1 = (int *)calloc(1, sizeof(int));
 num2 = (int *)calloc(1, sizeof(int));
 num1= 5.8 , num2 = 6.5;
 minimum = (*num1 < *num2) ? *num1 : *num2;
 printf("%d\n", minimum);
 free(num1);
 free(num2);
```

## Output:

<img width="627" height="295" alt="image" src="https://github.com/user-attachments/assets/499a030c-78d6-45ee-a3a2-8254b0ad3c00" />


## Result:
Thus the program was executed and the output was verified successfully.
