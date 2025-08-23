#include<stdio.h>
#include<conio.h>

void main()
{
 int n1, n2;
 char op;
 
 printf("Enter n1:");
 scanf("%d", &n1);

 printf("Enter n2:");
 scanf("%d", &n2);

 printf("Enter the operator:");
 scanf("\n%c", &op);
 
 if (op=='+')
 {
 printf("sum : %d", n1+n2);
 }
 
 else if(op=='-')
 {
 printf("diff : %d", n1-n2);
 }
 
 else if(op=='*')
 {
 printf("product : %d", n1*n2);
 }
 
 else if(op=='/')
 {
 printf("quotient : %d", n1/n2);
 }
 
 else{
 printf("invalid character");
 }
 getch;
 }
