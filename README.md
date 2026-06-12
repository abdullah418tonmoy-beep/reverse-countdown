#include<stdio.h>

int main()
{
    int n;

    printf("Enter last num: ");
    scanf("%d",&n);
    while(n>=1)
    {
        printf("%d. Blastoff! \n",n);
        n--;
    }


    return 0;
}
