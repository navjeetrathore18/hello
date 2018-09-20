#include<stdio.h>
#include<conio.h>
void main()
{
int a[],n,sum;
printf("enter the size of array");
scanf("%d",n);
printf("enter array elements");
for(i=0;i<n;i++)
{scanf("d",a[i]);
sum=sum+i;
}
printf("the sum of array elements are %d",sum);
getch();
}
