# A simple programme on "GOTO" statement
 A simple programme on "GOTO" statement To understand how it works and mark one thing that most of the devrloper or programmer preffered to avoid "GOTO" statement cause its very confusing for them 
#include<stdio.h>
int main()
{
    label:
      printf("we are inside label");
      goto end;

      goto label;

      end:
      printf("we are  at end");
      


      return 0;
}