#include <stdio.h>

int findMax(int a,int b);
void printAns(int max);

int main()
{
    int x,y,max;
    printf("Enter to numbers?");
    scanf("\n %d \n %d",&x,&y);

   findMax(x,y);
   printAns(max);

   return 0;
}
int findMax(int a,int b)
{
    int maxVal;
    if(a>b)
        maxVal=a;
    else
        maxVal=b;
    return maxVal;
}
void printAns(int max)
{
    printf("The maximum value is %d",max);
}

