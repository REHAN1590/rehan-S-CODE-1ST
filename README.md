# rehan-S-CODE-1ST
#include <stdio.h>
#include <conio.h>
int main()
{
    int x;
    printf("which subject's quice you have given");
    printf(" \n if maths than put 1 \n if science than put 2 \n if both than 4 ");
    scanf("%d",&x);
    if (x<=1) 
    {
        printf("  you have given maths quice");
        printf(" you were passed");
        printf(" you got 15 rupee");
    }
    if (x<=2)
    {
        printf(" you have given science quice");
        printf(" you were passed");
        printf(" you got 15 rupee");
    }
    if (x<=4)
    {
    printf(" you have given both quice");
        printf(" you were passed");
        printf(" you got 45 rupee");
    }
    return 0;
}
