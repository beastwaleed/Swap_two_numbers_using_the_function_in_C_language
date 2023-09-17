# Swap-two-numbers-using-the-function-in-C-language
A program in C to swap two numbers using a function
Copy and Paste this Souce code in your text editor

#include<stdio.h>
 	int swap1(int num1,int num2);
 	int swap2(int num1, int num2);

int main(){
 	
 	int num1, num2;
 	printf("enter numbers you want to swap= ");
 	scanf("%d %d", &num1, &num2);
 	
 		printf("Numbers we got after swaping are = %d and %d ",swap1(num1, num2), swap2(num1, num2));
 
 return 0;
 }
 
 //Function for swap1
 int swap1(int num1, int num2){
 
 return (num1*0)+num2;
 }
 
 //Function for Swap2
 
 int swap2(int num1, int num2){
 
 return (num2*0)+num1;
 }
 
 //Credits: Github:BeastWaleed
