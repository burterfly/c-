# c
练习题目
#include<stdio.h>

int main()
{
/*	//下三角的变量 
	int num=0;
	int i=0;
	int j=0;
	int h=0;
	
//上三角的变量 
	int a=0;
	int b=0;
	int c=0;
	scanf("%d",&num);
	
	//上三角 
	for (a=0;a<num;a++)
	{
		for(c=0;c<num-a;c++)
		{
			printf(" ");
		}
		for(b=0;b<a*2-1;b++)
		{
			printf("*");
		}
		printf("\n"); 
	}
	
//下三角	
for(i=0;i<num;i++)
{
		for(h=0;h<i;h++)
		{
		printf(" "); 
		}
	for (j=0;j<(num-i)*2-1;j++)
	{

		printf("*");
	
	}
printf("\n");
}*/





//冒泡     在这个题目中  i代表大循环  循环几次    j代表小循环  数组下标 

/*
int  a[5]={14,52,63,96,85};
int j=0;
int i=0;
for(i=0;i<5;i++)
 {
 	for(j=1;j<5-i;j++)
 	{
	 
 	if(a[j-1]<a[j])
 	{
	 int trm=a[j-1];
 	a[j-1]=a[j];
 	a[j]=trm;
	 	}
		}
		 }
 for(i=0;i<5;i++)
 {printf("%d\n",a[i]);
 }
 */
 

 
 
 
 //数组的倒置
 
  /*
 int  a[5]={12,45,85,96,456};
 int j=0;
 int  max=4;
 int min=0;
 while(max>min)
 {
 	j=a[max];
 	a[max]=a[min];
 	a[min]=j;
 	min++;
 	max--;
  } 
  for(j=0;j<5;j++)
  {
  	printf("%d\n",a[j]);
  }
  
  */
  
 
  
  //水仙花数问题，从100到1000
  
   /* 
  int n=0;
  int a=0;
  int b=0;
  int c=0;
for(n=100;n<399;n++)
{
	a=n/100;		//百位数 
	b=n%10;			//个位数 
	c=n/10%10;		//十位数 
//	if (a*a*a+b*b*b+c*c*c=n)   错误的写法   里面是判断
if((a*a*a+b*b*b+c*c*c)==n) 
	{
	printf("%d\n",n);
	 } 
 } 
   
   
   */
   
 
 
   
  // 求素数问题
   
 /*  int i=0;
   int j=0;
  // int sta=1;   不能写在循环外面  不然sta的值修改后就不能变回来 
   for (i=3;i<100;i++)
   {
   
   int sta=1;  //必须写在循环里面 
   	for(j=2;j<i;j++)
   	      {
   		if((i%j)==0)  //不是素数 
		   {
		   	sta=0;
		   	break;
		   }
	 
	 	
		  }	
		 
    if(sta==1)  //写在第一个循环里面，在第二个循环外面 
		  {printf("%d\n",i);
		  }
   }
   
   
   */
 //求数组中的最大值 
 
 /*  
  int  a[5]={14,52,63,96,85};
int j=0;
int i=0;
for(i=0;i<5;i++)
 {
 	for(j=1;j<5-i;j++)
 	{
	 
 	if(a[j-1]<a[j])
 	{
	 int trm=a[j-1];
 	a[j-1]=a[j];
 	a[j]=trm;
	 	}
		}
		 }

 {printf("%d\n",a[0]);
 } 
   
   
   //另一种方法 
   
  int  a[5]={14,52,63,96,85};
int max=a[0];
int j=0;
int i=0; 
   for(i=1;i<5;i++)
   {
   	if (max<a[i])
	   {
	   	j=max;
	   	max=a[i];
	   	a[i]=j;
	   }
   }
   printf("%d\n",max);
   
 */  
   
/*   
   //求数组中所有元素的和 
int  a[5]={1,1,100,1,100};
int j=0;
int i=0;
   
   for(i=0;i<5;i++)
   {
   	j=j+a[i];
	} 
   printf("%d\n",j);
   
   */
 /*  
   //求数组中的奇数的和
   int  a[5]={14,52,63,96,85};
int j=0;
int i=0;
for(i=0;i<5;i++)
{
	if(a[i]%2==1)
	{
		j=j+a[i];
	
	}
	
 } 
 	printf("%d\n",j);  //此时的printf写在循环外面 
   
 */  
   
   
   
   
   
   
   
   
   
   
   
   
   
   
	return 0;
 } 
 
