#include<stdio.h>
int main(){
int first,second,*p,*q,sum;
printf("enter the two intengers to add\n");
scanf("%d%d",&first,&second);
p=&first;
q=&second;
sum=*p + *q;
printf("sum of entered numbers=%d\n",sum);
return 0;
}
