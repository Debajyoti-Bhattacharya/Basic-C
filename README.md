# Basic-C
Addition of two integers in C Programing
#include<stdio.h>
int main()
{
int num1,num2,num3,num4,sum;
printf("Enter the four integers:");
scanf("%d%d%d%d",&num1,&num2,&num3,&num4);
sum = num1+num2+num3+num4;
printf("%d+%d+%d+%d=%d",num1,num2,num3,num4,sum);
return 0;
}
