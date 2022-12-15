## Program 23:Write a code to find the factorial of a number.
```C
#include <stdio.h>
int main()
{
int num,fact=1,i;
printf("Enter the number to find its fictorial: ");
scanf("%d",&num);
for(i=1;i<=num;i++)
{
    fact=fact*i;
}
printf("The factorial of %d is %d",num,fact);
    return 0;
}
```C
**Output:
Enter the number to find its fictorial: 6
The factorial of 6 is 720**
