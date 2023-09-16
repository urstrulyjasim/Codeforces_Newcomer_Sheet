#include<stdio.h>
#include<string.h>
 
int min(int a, int b)
{
   if(a<b)
      return a;
   else
      return b;
}
 
int main()
{
   char s[1000000];
   gets(s);
   int len = strlen(s);
   int e=0, g=0, y=0, p=0, t=0;
   for(int i=0; i<len; i++)
   {
      if(s[i] == 'e' || s[i] == 'E')
         e++;
      else if(s[i] == 'g' || s[i] == 'G')
         g++;
      else if(s[i] == 'y' || s[i] == 'Y')
         y++;
      else if(s[i] == 'p' || s[i] == 'P')
         p++;
      else if(s[i] == 't' || s[i] == 'T')
         t++;
   }
   int min1 = min(e,g);
   int min2 = min(y,p);
   int min3 = min(min1,min2);
   
   printf("%d", min(min3, t));
   
   
   return 0;
}
