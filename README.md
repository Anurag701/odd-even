# odd-even

/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>

int main()
{   int num,i;
    printf("Enter the number = ");
    scanf("%d",&num);
    if(num%2==0)
    {
        printf("%d is even number",num);
        for(i=0;i<=num;i++)
        printf("Anurag Loves Riya\n");
    }
        
    else
    {
        printf("%d is odd number",num);
        for(i=0;i<=num;i++)
        printf("Anurag Is a very good boy\n");
    }
        
    return 0;
}
