# EX 39 C program to find sum of digits.
## DATE:21/05/2025
## AIM:
To write a C program to find sum of digits.

## ALGORITHM:
1. Start.
2. Define a variables.
3. Write a program to print the sum of digits.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,s,i,y=0;
    scanf("%d",&a);
    for(i=1;i<=5;i++)
    {
        s=a%10;
        y=y+s;
        a=a/10;
    }
    printf("%d",y);
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/ffa79ef8-ac73-4014-81b4-696cc5049e34)
## RESULT:
Thus the program was executed and the output was verified successfully.

