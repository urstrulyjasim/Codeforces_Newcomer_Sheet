#include <stdio.h>
#include <string.h>
 
int main() 
{
   int arr[26] ={0};
   int size;
   scanf("%d", &size);
   for(int i=0; i<=size; i++)
   {
      char c;
      scanf("%c", &c);
      arr[(int)c - 97]++;
   }
   for(int i=0; i<=25; i++)
   {
      while(arr[i]!=0)
      {
         printf("%c", (char)(i+97));
         arr[i]--;
      }
   }
   
   return 0;
}
