#include <stdio.h>
int add(int a, int b);         // function prototype

int main(){
    int n1,n2,sum;
    scanf("%d %d",&n1,&n2);
    sum = add(n1, n2);        // function call
    printf(" %d",sum);
    return 0;
}
int add(int a, int b)    {// function definition
    int result;
    result = a+b;
    return result;                  // return statement
}
