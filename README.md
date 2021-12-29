# c-programming
#include<stdio.h>
main()
{
  int n,rev=0,b,m;
  printf("enter the number");
  Scanf("%d",&n);
  b=n;
  while(n!=0)
  {
      m=n%10;
      rev=rev*10+m;
      n=n/10;
   }
   if(b==rev)
   {
       printf("The number is palindrom");
    }
    else
    {
         printf("The number is not palindrom");  
    }
 }
   
