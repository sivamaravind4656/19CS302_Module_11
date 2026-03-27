# EX 55 C program to find a square of number using function with arguments without return type.
## DATE:
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## Algorithm
1.Define a function square() that takes an integer as an argument.

2.Inside the function, calculate the square of the number by multiplying it by itself.

3.Print the square of the number inside the function.

4.Call the square() function from main(), passing the number as an argument.

5.Ensure that there is no return value (void return type).

 

## Program:
```
/*
C program to find a square of number using function with arguments without return type.
Developed by: ARAVINDHAN K A P
RegisterNumber: 212222063001
*/
#include <stdio.h>

void square(int num)
{
    printf("Square of %d is %d\n", num, num * num);
}

int main()
{
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    square(num);

    return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/54a9d34b-4d75-4a6f-9d7e-8f20fefa6e9d)


## Result:
Thus the program was executed and the output was verified successfully.
