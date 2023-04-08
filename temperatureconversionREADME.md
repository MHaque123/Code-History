#include<stdio.h>
int main()
{ int choice;
float celcius,fahrenheit;
 printf("Temperature conversion menu:\n");
 printf("For getting celcius to fahrenheit value press 1\n");
 printf("For getting fahrenheit to celcius value press 2\n") ;
 printf("Enter your choice\n",choice);
 scanf("%d",&choice);

switch(choice)
    {
      case 1:
          {
          printf("Enter celcius temperature\n");
          scanf("%f",&celcius);
         fahrenheit=(1.8*celcius)+32;
         printf("The temperature in fahrenheit is=%f",fahrenheit);

      }

     case 2:{
     printf("Enter fahrenheit temperature\n");
          scanf("%f",&fahrenheit);
         celcius=(fahrenheit-32)/1.8;
         printf("The temperature in celcius is=%f",celcius);

      }






    }




  return 0;
}
