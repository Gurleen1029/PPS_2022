## Program 20: Write a code to display the use of printf and scanf.
```C
#include <stdio.h>
int main()
{
    char chr;
    printf("Please enter a suitable character");
    scanf("%c",&chr);
    printf("The character you entered is%c",chr);
    return 0;
}
```C
**Output:Please enter a suitable character b
The character you entered is b**
