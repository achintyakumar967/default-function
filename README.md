# default-function
// Online C compiler to run C program online
#include <stdio.h>
int swap();
int add();
int main() {
     int c,d;
 printf("enter two number");
 scanf("%d %d",&c,&d); 
 printf("\n the number before swaping are %d and %d",c,d);
 swap(c,d);
 add();  
}
int swap(int a,int b){
 b=a+b-(a=b);
 printf("\n the number after swaping are %d and %d\n",a,b);
 
    return 0;
} 
int add(){
    int a,b;
    printf("enter a number :");
    scanf("%d%d",&a,&b);
    a=+b;
    printf("add=%d",a);
}
