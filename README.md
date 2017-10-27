#include<stdio.h>
void main()
{
	int a,b,c,max,mid,min,t;
	  printf ("Please enter the three integers that you want compare\n");
      printf ("Please enter first number\n");
      scanf ("%d", &a);
      printf ("Please enter second number\n");
      scanf ("%d", &b);
      printf ("Please enter third number\n");
      scanf ("%d", &c);

	t=a>b;
	switch(t){
	case 0:
		max=b; break;
	case 1:
		max=a; break;
	}
	t=max>c;
	switch(t){
	case 0:
		max=c; break;
	}
	t=a<b;
	switch(t){
	case 0:
		min=b; break;
	case 1:
		min=a; break;
	}
	t=min<c;
	switch(t){
	case 0:
		max=c; break;
	
	printf("max=%d\n",max);
	printf("mid=%d\n",mid);
	printf("min=%d\n",min);
