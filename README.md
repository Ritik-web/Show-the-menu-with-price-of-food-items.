#include<stdio.h>
void main()
{
	int number;
	printf("Enter your number ");
	scanf("%d",&number);
	if(number>5)
	{
		printf("Wrong Entry");
	}
	else if(number==1)
	{
		printf("Food item - Sandwich");
		printf("\nPrice - Rs 149");
	}
	else if(number==2)
	{
		printf("Food item - French Fries");
		printf("\nPrice - Rs 99");
	}
	else if(number==3)
	{
		printf("Food item - Pasta");
		printf("\nPrice - Rs 179");
	}
	else if(number==4)
	{
		printf("Food item - Burger");
		printf("\nPrice - Rs 129");
	}
	else if(number==5)
	{
		printf("Food item - Pizza");
		printf("\nPrice - Rs 239");
	}
}
