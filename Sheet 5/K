#include <stdio.h>
#include <stdlib.h>
#define s 100001
 
void print1(int arr[s], int shift, int size)
{
   for(int i=shift; i<size; i++)
   {
      printf("%d ", arr[i]);
   }
}
void print2(int arr[s], int shift)
{
   for(int i=0; i<shift; i++)
   {
      printf("%d ", arr[i]);
   }
}
 
 
int main() 
{
   int size, times;
   scanf("%d%d", &size, &times);
   int arr[size];
   for(int i=0; i<size; i++)
   {
      scanf("%d", &arr[i]);
   }
   int shift = times % size;
   print1(arr, (size-shift), size);
   print2(arr,(size-shift));
   
   return 0;
}
