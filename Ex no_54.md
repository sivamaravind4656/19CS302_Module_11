## print all the letters of the English alphabet.

SAMPLE OUTPUT : CAPS and add space to each alphabet

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z

# EX 54 C program to reverse a string.
## DATE: 
## AIM:
To write a C program to reverse a string.

## Algorithm
1.Use a loop to iterate over the ASCII values of uppercase English letters (from 'A' to 'Z').

2.Start from the ASCII value of 'A' (65) and loop until the ASCII value of 'Z' (90).

3.In each iteration, print the current letter followed by a space.

4.Print a newline after printing all the letters.

5.Ensure that each letter is separated by a space.

## Program:
```
/*
C program to reverse a string.
Developed by: ARAVINDAN K A P
RegisterNumber:  212222063001
*/
#include <stdio.h>

int main()
{
    for(char ch = 'A'; ch <= 'Z'; ch++)
    {
        printf("%c ", ch);
    }
    printf("\n");

    return 0;
}



```

## Output:

![image](https://github.com/user-attachments/assets/a2a8d2f2-1655-435f-8484-c7cac4924033)


## Result:
Thus the program was executed and the output was verified successfully.








