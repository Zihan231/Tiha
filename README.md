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

