# C4
// program
#include<stdio.h>
int main(){
    int loop,n;
    loop=1;
    printf("enter the value of n:");
    scanf("%d",&n);
    while(loop<=n){
        if(loop%2==1){
            printf("%d ",loop);
            
        }
        loop++;
    }
    return 0;
}
