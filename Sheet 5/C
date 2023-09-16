#include <stdio.h>
#include <stdlib.h>
#define s 10000
 
int index = 0;
int *binary(int num)
{
   int bi[100];
   while(num!=0)
   {
      bi[index] = num % 2;
      num /= 2;
      index++;
   }
   return bi;
}
int pallindrome(int arr[s])
{
   for(int i=0, j=index-1; i<index, j>=0; i++,j--)
      if(arr[i] != arr[j])
         return 0;
   return 1;
}
 
 
int main() 
{
   int num;
   scanf("%d", &num);
   if(num%2 == 0)
   {
      printf("NO\n");
      return 0;
   }
   int index = 0;
   int bi[100];
   
   while(num!=0)
   {
      bi[index] = num % 2;
      num /= 2;
      index++;
   }
   for(int i=0, j=index-1; i<index, j>=0; i++,j--)
      if(bi[i] != bi[j])
      {
         printf("NO\n");
         return 0; 
      }
   printf("YES\n");
   
   
   return 0;
}
