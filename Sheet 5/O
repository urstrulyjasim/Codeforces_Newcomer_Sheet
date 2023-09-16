#include <stdio.h>
#include <stdlib.h>
#define s 1000
 
void sort(int a[s], int n)
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
 
int countDivisor(int num)
{
    int m = num/2;
    int count = 0;
    for(int i=1; i<=m; i++)
        if(num % i == 0)
            count++;
        
    return count;
}
 
int palindrome(int num)
{
    int temp = num;
    int sum = 0;
    int a;
    while(num>0)
    {
        a = num % 10;
        sum = (sum*10) + a;
        num /= 10;
    }
    if(temp == sum)
        return 1;
    else
        return 0;
}
 
int main() 
{
    int n;
    scanf("%d", &n);
    int arr[n];
    for(int i=0; i<n; i++)
        scanf("%d", &arr[i]);
    sort(arr, n);
    printf("The maximum number : %d\n", arr[n-1]);
    printf("The minimum number : %d\n", arr[0]);
    int countPrime = 0;
    int countPalindrome = 0; 
    for(int i=0; i<n; i++)
    {
        if(palindrome(arr[i]))
        {
            countPalindrome++;
        }
        int m = arr[i] / 2;
        int flag = 0;
        for(int j=2; j<=m; j++)
        {
            if(arr[i] % j == 0)
            {
               flag=1;
               break;
            }
        }
        if(flag==0 && arr[i] != 1)
            countPrime++;
    }
    printf("The number of prime numbers : %d\n", countPrime);
    printf("The number of palindrome numbers : %d\n", countPalindrome);
    int c, index;
    int max;
    for(int i=0; i<n; i++)
    {
        c = countDivisor(arr[i]);
        if(i==0)
        {
            max = c;
            index = i;
        }
        else
            if(c >= max)
            {
                max = c;
                index = i;
            }
    }
    printf("The number that has the maximum number of divisors : %d\n", arr[index]);
    
 
    return 0;
}
