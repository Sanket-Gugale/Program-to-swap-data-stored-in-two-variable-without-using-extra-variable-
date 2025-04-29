# Program-to-swap-data-stored-in-two-variable-without-using-extra-variable-
#include<stdio.h>
int main ()
{
   int a=5,b=10;
   a=a+b;
   b=a-b;
   a=a-b;
   printf("After swapping without using extra variable:\n");
   printf("a=%d\n",a);
   printf("b=%d\n",b);
   return 0;
 }
