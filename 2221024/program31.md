## Program 29: Write a program to swap two numbers without using a third variable
``` 
#include <stdio.h>
int main()
{
int n1,n2;
printf("Enter first number -> ");
scanf("%d",&n1);
printf("Enter second number -> ");
scanf("%d",&n2);
n1 = n1+n2;
n2 = n1-n2;
n1 = n1-n2;
printf("\nAfter swapping:\n");
printf("First number -> %d\n",n1);
printf("Second number -> %d\n",n2);
return 0;
}
```
**Output:Enter first number -> 7
Enter second number -> 9
After swapping:
First number -> 9
Second number -> 7**
