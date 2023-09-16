#include <stdio.h>
#include <stdlib.h>
#define s 10000
 
int countNumber(int arr[s], int size)
{
    int count=0;
    for(int i=0; i<size; i++)
    {
        if(arr[i] != arr[i-1])
            count++;
    }
    return count;
}
void asc_sort(int a[s], int n)
{
 int i, j, temp;
 for(i=0;i< n-1;i++)
    for(j=i+1;j< n;j++)
        if(a[i]>a[j])
       {
        temp = a[i];
        a[i] = a[j];
        a[j] = temp;
       }
}
 
int main() 
{
    int n;
    scanf("%d", &n);
    if(n==0)
    {
        printf("0");
        return 0;
    }
    int arr[n];
    for(int i=0; i<n; i++)
    {
        scanf("%d", &arr[i]);
    }
    asc_sort(arr,n);
    printf("%d", countNumber(arr,n));
        
 
    return 0;
}
