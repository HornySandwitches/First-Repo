#include<stdio.h>
float Addition();
int main()
{
	float d;
	d= Addition();
	printf("%f",d);
}

float Addition()
{
	float a,b,c;
	printf("Enter first number: ");
	scanf("%f",&a);
	printf("Enter second number: ");
	scanf("%f",&b);
	c=a+b;
	return c;
}
