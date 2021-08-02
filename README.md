# Swapping-Of-Two-Numbers-Without-3rd-Variable
Developed By Darun
#include<stdio.h>
int main()
{
 int a=10,b=20;
 printf("Before swapping a=%d and b=%d",a,b);
 a=a+b;
 b=a-b;
 a=a-b;
 printf("After swapping a=%d and b=%d",a,b);
 return 0;
}
