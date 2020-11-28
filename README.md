# computer-assignment-II
PROGRAMS
#include <stdio.h>

void main()
{
   int num,count=0;
   printf("TO FIND NUMBER OF DIGITS IN NUMBER\n");
   printf("------------------------------------\n");
   printf("enter the required number:\n");
   scanf("%d",&num);
   while(num!=0)
   {
       num/=10;
       ++count;
   }
   printf("number of digits are:%d\n",count);
   
}
