#include <stdio.h>

int main(void)
{
    int a,i,b;
    char r='*';
    int w=1;
    scanf("%d",&a);
    b=a;
    
    while(w<=a){
      printf("%*c",b,' ');  
             
          for(i=1;i<=w;i++){
           printf("%c ",r);
          }
      printf("\n");
      w++;
      b--;
        
    }


    return 0;
}
