#include<stdio.h>
void findFactorial(int,int *); 
int main(){
 int i,factorial,n;
 printf("Enter a number: ");
 scanf("%d",&n);
 findFactorial(n,&factorial);
 if(n>0)
 printf("Factorial of %d is: %d",n,factorial);
 else{
 	printf("invalid");
 }
 return 0;
}
 
void findFactorial(int n,int *factorial){
 int i;
 
 *factorial =1;
 
 for(i=1;i<=n;i++)
 *factorial=*factorial*i;
}
