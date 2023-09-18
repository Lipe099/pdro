# include  <stdio.h>


     int main() {

     int num, total;

     printf("digite um numero : ");
     scanf("%d", &num);

     while ( num%2==0){

         printf("digite um numero : ");
         scanf("%d", &num);
        total ++;
     }

   printf(" a quantidade de numeros pares foi %d ", total);
    
     }
