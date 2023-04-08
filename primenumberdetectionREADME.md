#include<stdio.h>
int main()
{ int num,i,count=0;
  printf("Enter a positive value");
  scanf("%d",&num);
  for(i=2;i<num;i++)
    {  if(num%i==0)
       {count++;
        break;
        }
    }
  if(count==0)
    printf("PRIME NUMBER");
    else
        printf("NOT PRIME NUMBER");


    return 0;
}
