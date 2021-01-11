//# Let-Us-C-chapter1-4question
#include<stdio.h>
int main(){
float tempinc,tempinfarenheit;
printf("Enter temperature in farenheit:");
scanf("%d",&tempinfarenheit);
tempinc=9.0/5.0*tempinfarenheit+32;
printf("Temperature in centigrade is %f",tempinc);
return 0;
}
