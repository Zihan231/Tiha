# Tiha

# Check Even or Odd Program in C

This program checks whether a given integer is even or odd.

```c
#include <stdio.h>

int main() {
    int num;
    printf("Enter an integer: ");
    scanf("%d", &num);

    if (num % 2 == 0)
        printf("%d is even.\n", num);
    else
        printf("%d is odd.\n", num);
    
    printf("----------------\n");
    printf("Coded by Tihamun\n");
    return 0;
}
````
