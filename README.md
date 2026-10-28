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
```c

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;
    srand(time(0));

    scanf("%d", &n);

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}

```
# OUTPUT:
<img width="707" height="537" alt="image" src="https://github.com/user-attachments/assets/d3518881-b996-4f91-8c41-49ec057d58c6" />

# RESULT:
Thus, the C program to generate pseudorandom numbers using the standard library was implemented successfully.
