-#include<stdio.h>
void main()
{
    int num;
    printf("enter the number:");
    scanf("%d",&num);
    switch(num)
    
    {
    case 1:
       printf("pizza");
       break;
    case 2:
       printf("burger");
       break;
    case 3:
       printf("french fries");
       break;
       
    default:
       printf("invalid choice");
       break;
    }
}
