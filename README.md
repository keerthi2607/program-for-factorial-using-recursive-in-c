
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int n;
    printf("Enter the factorial number:\n");
    scanf("%d",&n);
    printf("%d",fact(n));

}
int fact(int n)
{
    if(n==0)
    {
        return 1;
    }
    else
    {
        return n*fact(n-1);
    }
}
