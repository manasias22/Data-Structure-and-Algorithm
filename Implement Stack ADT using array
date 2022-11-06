

#include<stdio.h>
#include<conio.h>

#define SIZE 10

int top=-1;
int stack[SIZE];
int i;

void push();
void pop();
void peek();
void display();

void main()
{
	int choice;
	clrscr();

	printf("---Stack Implementation---\n\n");

	while(1)
	{
		printf("\nOperations performed by Stack");
		printf("\n1.Push\n2.Pop\n3.Peek\n4.Display\n5.End");
		printf("\n\nEnter the choice: ");
		scanf("%d",&choice);

		switch(choice)
		{
			case 1:
				push();
				break;
			case 2:
				pop();
				break;
			case 3:
				peek();
				break;
			case 4:
				display();
				break;
			case 5:
				exit(0);
				break;
			default:
				printf("\nInvalid choice\n");
		}
	}

}

void push()
{
	int x;

	if(top==SIZE-1)
	{
		printf("\nOverflow\n");
	}
	else
	{
		printf("\nEnter element to be inserted to the stack: ");
		scanf("%d",&x);
		top++;
		stack[top]=x;
	}
}

void pop()
{
	if(top==-1)
	{
		printf("\nUnderflow\n");
	}
	else
	{
		printf("\nPopped element:  %d\n", stack[top]);
		top--;
	}
}

void peek()
{
	if(top==-1)
	{
		printf("\nUnderflow\n");
	}
	else
	{
		printf("\nThe topmost element:  %d\n",stack[top]);

	}
}

void display()
{

	if(top==-1)
	{
		printf("\nUnderflow\n");
	}
	else
	{
		printf("\nElements present in the stack: \n");
		for(i=top;i>=0;--i)
		{
			printf("%d\n",stack[i]);
		}
	}
}









