#include<stdio.h>
#include<string.h>
 
int main()
{
   int n;
   scanf("%d", &n);
   while(n--)
   {
      char s1[100];
      scanf("%s", &s1);
      char s2[100];
      scanf("%s", &s2);
      int len1,len2,x,y;
      len1=strlen(s1);
      len2=strlen(s2);
   
      if(len1<len2)
      {
        x=len1;
        y=len2;
      }
      else
      {
        x=len2;
        y=len1;
      }
      if(len1==len2)
         x=len1;
           
      for(int i=0;i<x;i++)
         printf("%c%c", s1[i], s2[i]);
      if(len1!=len2)
      {
       if(len2<len1)
       for(int i=x;i<y;i++)
           printf("%c",s1[i]);
       else
         for(int i=x;i<y;i++)
             printf("%c", s2[i]);
      }
   printf("\n");
      
   }
   return 0;
}
