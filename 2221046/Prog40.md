## Program 40: Write a program to calculate Factorial of a number
```C
#include <stdio.h>

long int fact(int n)

{

if(n<=1)return 1;

else return fact(n-1)*n;
}

int main()

{

int n;

printf("Enter a number: ");

scanf("%d",&n);

printf("Factorial of %d = %ld\n",n,fact(n));

return 0;
}
```C
**Output:Enter a number: 7

Factorial of 7 = 5040**
