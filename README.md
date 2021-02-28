
#include <stdio.h>
main()
{
int n;
printf("\enter the number");
scanf("%d",&n);
if(n>=85)
{
printf("A grade");
}
else if(n>=70)
{
printf("B grade");
}
else if(n>=55)
{
printf("c grade");
}
else if(n>=40)
{
printf("D grade");
}
else if(n<40)
{
printf("F grade");
}
}
