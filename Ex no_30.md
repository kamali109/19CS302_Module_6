# EX 30 C program to add two integer elements in an array using realloc() and that array already has three elements.
## AIM:
To write a C program to add two integer elements in an array using realloc() and that array already has three elements.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
C program to add two integer elements in an array using realloc() and that array already has three elements.

Developed by: KAMALI.S
RegisterNumber:  212222060109 
*/
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *arr, size, i;
 size = 3;
 arr = (int *)malloc(size * sizeof(int)); 
 for (i = 0; i < size; i++) {
 arr[i] = i * 10; }
 printf("Original array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }
 printf("\n");
 size *= 2;
 arr = (int *)realloc(arr, size * sizeof(int)); 
 for (i = size / 2; i < size; i++) {
 arr[i] = i * 10;
printf("Updated array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }}
```

## Output:
<img width="458" height="233" alt="image" src="https://github.com/user-attachments/assets/6733d055-2bbc-47c9-a6b2-243540b9d107" />



## Result:
Thus the program was executed and the output was verified successfully.
