# EX 53 C program to remove duplicates in an array.
## DATE:
## AIM:
To write a C program to remove duplicates in an array.

## Algorithm
1.Define a function remove_duplicates() to remove duplicate elements from an array.

2.Iterate through each element in the array and check if it already exists in the result array.

3.If it doesn't exist, add it to the result array.

4.Return the length of the array after removing duplicates.

5.Print the updated array. 

## Program:
```
/
*/

#include <stdio.h>

void remove_duplicates(int arr[], int *size)
{
    int i, j, k;

    for(i = 0; i < *size; i++)
    {
        for(j = i + 1; j < *size; j++)
        {
            if(arr[i] == arr[j])
            {
                for(k = j; k < *size - 1; k++)
                    arr[k] = arr[k + 1];
                (*size)--; // Decrease the size of the array
                j--;
            }
        }
    }
}

void display(int arr[], int size)
{
    for(int i = 0; i < size; i++)
        printf("%d ", arr[i]);
    printf("\n");
}

int main()
{
    int arr[] = {1, 2, 3, 2, 4, 3, 5};
    int size = sizeof(arr) / sizeof(arr[0]);

    printf("Original array: ");
    display(arr, size);

    remove_duplicates(arr, &size);

    printf("Array after removing duplicates: ");
    display(arr, size);

    return 0;
}

```

## Output:

![image](https://github.com/user-attachments/assets/543856cc-9abf-4150-a4ad-9fb2903a01db)

## Result:
Thus the program was executed and the output was verified successfully.
