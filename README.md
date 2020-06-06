#include<stdio.h>
#include<conio.h>
void main();
{
int a,n,r=0;
clrscr();
printf("Enter a number");
scanf("%d",&n);
while(n!=0)
{
a=n%10;
r=r*10+a;
n=n/10;
}
printf("Reverse=%d",r);
getch();
}
