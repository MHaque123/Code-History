#include<stdio.h>
int main()
{
 int temp,num,sum=0,reminder;
  scanf("%d",&num);
  temp=num;
  while(temp!=0)
   {
       reminder=temp%10;
       sum=(sum*10)+reminder;
       temp=temp/10;
    }

   printf("%d",sum) ;

}
