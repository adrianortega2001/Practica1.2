# Practica1.2
1.2
/*practica1.1
Adrian ortega Perez
*/
#include<stdio.h>
#include<conio.h>
int main(void){
printf("1.Suma\n");
printf("2.Resta\n");
printf("Introduce 1 para la suma\n");
printf("Introduce 2 para la resta\n");
printf("Introduce 3 para la multiplicacion\n");
int opt;
scanf("%d",&opt);
int a;
int b;
printf("Introduce la primer cantidad:");
scanf("%d",&a);
printf("Intropduce la segunda cantidad:");
scanf("%d",&b);
int c;
if(opt==1){
c=a+b;
}
else{
if(opt==2){
c=a-b;
}
else{
if(opt==3){
c=a*b;
}
}
}
printf("El resultado es %d",c);
}
