#include<stdio.h>
int main()
{  int num1,num2;
   char oper;
  printf("Choose an operator(+,-,*,/)\n");
  scanf("%c",&oper);
  printf("Enter two numbers\n");
  scanf("%d %d",&num1,&num2);
  switch(oper)
   { case '*':{
       printf("%d*%d=%d\n",num1,num2,num1*num2);
 break;
   }

 case '+':
    {
      printf("%d+%d=%d\n",num1,num2,num1+num2);
      break;
    }


 case '-':
   {
       printf("%d-%d=%d\n",num1,num2,num1-num2);
  break;
   }

 case '/' :
    { printf("%d/%d=%d",num1,num2,num1/num2);
    break;

    }
 default :

        printf("Invalid operator");

}
return 0;
}

