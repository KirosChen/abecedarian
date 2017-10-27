/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/
#include<stdio.h>
void main()
{
	int a,b,c,t,max,min,mid;
	printf("Please enter the three integers that you want compare:\n");
	scanf("%d%d%d",&a,&b,&c);
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
	t= a<b;
	switch(t){
    	case 0:
		min=b; break;
    	case 1:
		min=a; break;
	}
	t=min>c;
	switch(t){
	    case 1:
	    min=c; break; 
	    
	}
	t= a <max && a> min;
	switch(t){
	    case 1 :
	    mid=a;
	    case 0 :
	    mid=b;
	}
	t= 
	
	
	
	
	printf("max=%d\n",max);
	printf("midlle=%d\n",mid)
	printf("min=%d\n",min);
}
