//# PROJETO
//V0.9

#include <stdio.h>

int main(){

int x;
int *px;
char *pcx;
x=257;
px=&x;
pcx=&x;
printf("x= %d\n",*px);
printf("x= %d\n",*pcx);
pcx=pcx+1;
printf("x= %d\n",*px);
printf("x= %d\n",*pcx);


return 0;}
