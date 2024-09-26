#include<stdio.h>
#include<stdlib.h>
#include<ctype.h>
#define max 100
int stack[max];
int top =-1;
void push(int ele)
{
if(top>=max-1)
{
printf("the stack is full");
}
else{
stack[++top]=ele;
printf("the element is pushed %d\n",ele);
}}
int pop()
{
if(top<0)
{
printf("the stack is empty");
}
else{
int ele=stack[top--];
printf("the element is popped %d\n",ele);
}
}
void display()
{
if(top<0)
{
printf("the stack is empty");
}
else{
printf("stack elements are:");
for(int i=0;i<=top;i++)
{
printf("%d\n",stack[i]);
}
printf("\n");
}
}
void palindrome()
{
if(top<0)
{
printf("stack is empty");
}
int ori[max],rev[max];int k=0;int flag=1;
for(int i=0;i<top;i++)
{
ori[max]=stack[i];
}
for(int j=top;j>=0;j--)
{
rev[++k]=stack[j];
}
for(int i=0;i<=top;i++)
{
if(ori[max]==rev[k])
{
flag =0; 
break;
}
}
if(flag)
{
printf("it is palindrome\n");
}
else
{
printf("it is not a plaindorome\n");
}
}
int main()
{
int ch;int ele;
do
{
printf("enter 1 for insertion\n");
printf("enter 2 for deletion\n");
printf("enter 3 for display\n");
printf("enter 4 for plaindrome\n");
printf("enter 5 for exit\n");
printf("enter your choice\n");
scanf("%d",&ch);
switch(ch)
{
case 1:
{
printf("enter the element to be inserted:\n");
scanf("%d",&ele);
push(ele);
break;
}
case 2:
{
pop();
break;
}
case 3:
{
display();
break;
}
case 4:
{
palindrome();
break;
}
case 5:
{
printf("exit");
break;
}
default:
{
printf("invalid choice");
break;
}
}}
while(ch!=5);
return 0;
}















