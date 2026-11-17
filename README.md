# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n;

    /* Seed the random number generator with the current time */
    srand(time(0));

    /* Get the number of random numbers to generate */
    printf("Enter how many random numbers to generate: ");
    scanf("%d", &n);

    /* Generate and print the numbers */
    printf("\nRandom numbers:\n");
    for (int i = 1; i <= n; i++)
        printf("%d. %d\n", i, rand());

    return 0;
}
```
# OUTPUT:
<img width="552" height="553" alt="image" src="https://github.com/user-attachments/assets/9fc7c178-3d42-44d2-b78b-5ee41a367e0f" />


