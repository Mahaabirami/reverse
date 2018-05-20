#include <stdio.h>
#include <stdlib.h>

int main()
{
    int n,r,a,b=0;
    printf("Enter n\n");
    scanf("%d",&n);
    r=n;
while(n>0)
{


   a=n%10;
   b=b*10+a;
   n=n/10;
}

   printf("\n%d",r);
printf("\n%d",b);
    return 0;
}
