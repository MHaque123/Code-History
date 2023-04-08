#include<stdio.h>
int main()
{ int i,j;
printf("Enter a number");
scanf("%d",&i);
for(j=1;j<=10;j++)
{
printf("%dX%d=%d\n",i,j,i*j);

}

return 0;
}
