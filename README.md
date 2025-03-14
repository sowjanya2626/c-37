# c-37
Finding of max &amp; min of two numbers without using any loops or conditions constraints,use standard library function (abs) ise arthematic operators for evaluation 
#include <stdio.h>
#include<stdlib.h>
int main() 
{
int a=22,b=4;
printf("Max=%d\n",((a+b)+abs(a-b))/2);
printf("Min=%d\n",((a+b)-abs(a-b))/2);
    return 0;
}
