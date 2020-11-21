# Ivacenko.github.io

#include <stdio.h>

#include <stdlib.h>

#include <locale.h>

int main() 

{ 

setlocale(0, ""); 

int x, y, n; 

printf("\n Ведіть перше число "); 

scanf("%d", &x); 

printf("\n Ведіть друге число "); 

scanf("%d", &n);

y = x*n ;

printf("Результат y=%d", y); 

return 0;

}
