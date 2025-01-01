# Tiha

# 6. Check Even or Odd Program in C
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
```
# 7. Celsius to Fahrenheit

```c
#include <stdio.h>

int main() {
    float celsius, fahrenheit;

    printf("Enter temperature in Celsius: ");
    scanf("%f", &celsius);

    fahrenheit = (celsius * 9 / 5) + 32;

    printf("Temperature in Fahrenheit: %.2f\n", fahrenheit);

    printf("----------------\n");
    printf("Coded by Tihamun\n");

    return 0;
}
```
# 8. Sum of the Series
```c
#include <stdio.h>

int main() {
    int N, sum = 0;
    printf("Enter the value of N: ");
    scanf("%d", &N);

    for (int i = 1; i <= N; i++) {
        sum += i;
    }

    printf("Sum of the series: %d\n", sum);
    printf("----------------\n");
    printf("Coded by Tihamun\n");
    return 0;
}
```
# 9. Sum of Odd Series
```c
#include <stdio.h>

int main() {
    int n, sum = 0, i = 1;
    printf("Enter the value of n: ");
    scanf("%d", &n);

    while (i <= n) {
        sum += i;
        i += 2;
    }

    printf("Sum of the odd series: %d\n", sum);
    printf("----------------\n");
    printf("Coded by Tihamun\n");
    return 0;
}
```
# 10. Sum of the Squares of Even Numbers in a Series
```c
#include <stdio.h>

int main() {
    int n, sum = 0;

    printf("Enter the range (n): ");
    scanf("%d", &n);

    for (int i = 2; i <= n; i += 2) {
        sum += i * i;
    }

    printf("The sum of the squares of the even series up to %d is: %d\n", n, sum);
    printf("----------------\n");
    printf("Coded by Tihamun\n");

    return 0;
}
```
