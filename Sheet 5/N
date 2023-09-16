#include <stdio.h>
#include <stdlib.h>
#define s 1000

int counter(int size)
{
    int count=0;
    int arr[s];
    for(int i=0; i<size; i++)
    {
        scanf("%d", &arr[i]);
        if(arr[i]==0)
            count++;
        else
            printf("%d ", arr[i]);
    }
    return count;
}

int main() 
{
    int n;
    scanf("%d", &n);
    int zeros = counter(n);
    for(int i=0; i<zeros; i++)
    {
        printf("0 ");
    }
 
    return 0;
}
