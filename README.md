# Receba-10-numeros-e-retorne-o-quadrado-da-
#include <stdio.h>
#include <math.h>

int main(void)

{
    //Receba 10 numeros e retorne o quadrado da soma 
    
   float n, soma;
   
   for (int i=0; i <=10; i++) {
       printf ("\n Digite um numero:");
       scanf ("%f",&n);
       
       soma = soma + n;
   }
   
   printf ("Quadrado da soma dos 10 numeros:", pow(soma,2));
   
  return 0;
  
}
