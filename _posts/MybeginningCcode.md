This is a C code which delivers the value of a given number (positive for >0; negative for <=0)
```
#include <stdio.h>

int main(void)
{
    int x;

    printf("insert a number: ");
    scanf("%d", &x);

    if (x>0)
        printf("The value %d is positive\n", x);
    else
        printf("The value %d is negative or equal to 0\n", x);

    return 0;
}
```
