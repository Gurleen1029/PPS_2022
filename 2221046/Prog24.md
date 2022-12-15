## Program 24:Write a code to check whether the number is palindromic or not.
```C
#include <stdio.h>
int main()
{
    int num,sum=0,b,rem;
    printf("Enter the number here to check if it is palindromic: ");
    scanf("%d",&num);
    b=num;
    while(b>0)
    {
        rem=b%10;
        sum=sum*10+rem;
        b=b/10;
    }
    if(sum=num)
    printf("The number entered is Palindromic.");
    else
    printf("The number entered is not Palindromic.");
    return 0;
}
```C
**Output:
Enter the number here to check if it is palindromic: 121
The number entered is Palindromic.**
