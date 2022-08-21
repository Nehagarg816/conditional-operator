# conditional-operator
This is a program for conditional operator which is an alternative to 'if-else' decision control structure.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a,b;
	printf("Enter one number a:");
	scanf("%d",&a);
	b=a%2==0?1:0;
	printf("Value of b is %d",b);
}




Output:
Enter one number a:5
Value of b is 0
