#include<stdio.h>
#include<string.h>
 
int main()
{
   int N;
   scanf("%d", &N);
   char s[N];
   scanf("%s", &s);
   char temp;
   int count=0;
   for(int i=0; i<N; i++)
   {
      if(i == 0)
      {
         temp = s[i];
         count++;
      }
      else
      {
         if(s[i] != temp)
         {
            count++;
            temp = s[i];
         }
      }
   }
   printf("%d", count);
   
   
   return 0;
}
