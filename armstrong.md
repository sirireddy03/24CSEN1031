#include <stdio.h>

int main() {
    int n,r,sum=0,t;
    printf("\n Enter an integer number:");
    scanf("%d",&n);
    t=n;
    printf("\nThe given number= %d",n);
    while(n>0)
    {
    r = n%10;
    sum = sum+(r*r*r);
    n = n/10;
    }
    if(t==sum)
  { 
        printf("\n%d is Armstrong",t);
}
else
{
    printf("\n%d is not Armstrong",t);
}
return 0;
}
