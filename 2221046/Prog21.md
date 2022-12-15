## Program 21:Write a program to check whether a number is a prime or not.
```C
#include <stdio.h>
int main()
{
int num,i,count=0;
printf("Enter the number here: ");
scanf("%d",&num);
for(i=2;i<=num-1;i++)
{
    if(num%i==0){
        count=1;
        break;
    }
}
if(num==1)
{
    printf("1 is neither prime nor composite");
}
if(count==0)
{
    printf("Number is prime");
}
else
printf("Number is not prime");
    return 0;
}
```C
**Output:Write a positive interger:29
29 is a prime number**
