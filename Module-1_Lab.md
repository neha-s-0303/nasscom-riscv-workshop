## Lab 1: C Program to Compute Sum from 1 to N

### Objective
To write and execute a C program using the RISC-V GNU compiler toolchain to compute the sum of numbers from 1 to N.

### Program Code (`sum1ton.c`)
```c
#include <stdio.h>

int main() {
    int i, sum = 0, n = 9;
    for (i = 1; i <= n; i++) {
        sum += i;
    }
    printf("Sum from 1 to %d is %d\n", n, sum);
    return 0;
}

###Commands Used
gcc sum1ton.c
./a.out

###Output
Sum from 1 to 9 is 45

