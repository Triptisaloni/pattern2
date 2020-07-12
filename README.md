# pattern2
WAP to print a pattern:
  *
  *
*****
  *
  *

Sol.  
#include<stdio.h>
int main()
{
        int i = 0,j = 0;
    
    for(i=1; i<=5; i++)
{
        if(i == 3)
        {
  for(j =1; j <=5; j++)
            {
             printf("*");
            }
        }
        else
        {
    for(j=1; j<3 ; j++)
            {
                printf(" ");
            }
            printf("*");
        }
        printf("\n");
       }
       return 0;
}
