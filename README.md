# factorial
factorial recursive prg
#include <stdio.h>
int fact( int n);
int fact(int n)
{
    if(n==0 ||  n==1){
        return 1;
    }
    else 
    {return n*fact(n-1);}
}
int main() {
    int n;
    printf("enter  number ");
scanf("%d",&n);
printf("the factoial of %d %d",n ,fact(n));
    return 0;
}
