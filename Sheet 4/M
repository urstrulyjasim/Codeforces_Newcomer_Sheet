#include<stdio.h>
#include<string.h>
 
int main(){
 
   char s[10000], ch = 'h';
   gets(s);
   int len= strlen(s),flag = 0;
    for(int i=0; i<len; i++)
    {
      if(s[i]==ch)
      {
         flag++;
         if(flag == 1)
            ch = 'e';
         else if(flag == 2)
            ch = 'l';
         else if(flag==3)
            ch = 'l';
         else if(flag== 4)
            ch = 'o';
         else if(flag == 5)
            break;
      }
    }
    if(flag == 5)
        printf("YES");
    else
        printf("NO");
   
   return 0;
}
