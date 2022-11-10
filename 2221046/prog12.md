## Program:Write a code to display continue program.
```C
#include<stdio.h>
int main()
{
int i=0;
while(i<12)
{
if(i==6)
{
i++;
continue;
}
printf("%d\n",i);
i++;
}
return 0;
}
```C
**Output:0
1
2
3
4
5
7
8
9
10
11**
