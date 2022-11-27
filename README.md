//# factorial_for_loop.c//
#include<stdio.h>
int main()
{
    int i,no,fact=1;
    printf("Enter a number:");
    scanf("%d",&no);
    for(i=1;i<=no;i++)
    {
        fact=fact*i;
        printf("\nfact=%d",fact);
    }
    return 0;
}
