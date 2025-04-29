# EX 10 C PROGRAM TO FIND FACTORIAL OF THE GIVEN NUMBER
## DATE:28/04/2025
## AIM:
To write a C program to find the factorial of a given number.

## Algorithm
1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter factorial of the number.
6. End.

## Program:
```
#include <stdio.h>
int main() {
 int n, i;
 unsigned long long factorial = 1;
 scanf("%d", &n);
 if (n < 0) {
 printf("Factorial is not defined for negative numbers.\n");
 } else {
 for (i = 1; i <= n; i++) {
 factorial *= i;
 }
 printf("Factorial of %d = %llu\n", n, factorial);
 }
 return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/f58b29a1-d336-4f56-b272-7a46089f027d)




## Result:
Thus the program was executed and the output was verified successfully.
