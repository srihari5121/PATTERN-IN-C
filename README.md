# PATTERN-IN-C

#include<stdio.h>
int main()
{int num;
int row;
int col;
scanf("%d",&num);
for(row=1;row<num;row++)
{
      for(col=1;col<=num-row;col++)
        {printf("  ");
        }

       for(col=1;col<=row*2-1;col++)
        {printf("* ");
        }
         printf("\n");
}
for(row=num;row>=1;row--)
{
    for(col=1;col<=num-row;col++)
        printf("  ");

        for(col=1;col<=row*2-1;col++)
            printf("* ");

printf("\n");
}
return 0;
}
