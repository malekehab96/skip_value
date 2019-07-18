# skip_value
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int i,X,N;
    printf("Please enter the limit value \n");
    scanf("%i", &N);
    printf("Please enter the skip value \n");
    scanf("%i", &X);
for(i=0;i<=N;i++) {
  if(i % X == 0){
    continue;
  }
 printf("%i\t",i);
}
    return 0;
}
