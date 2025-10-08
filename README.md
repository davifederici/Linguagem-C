                        PRIMEIRO CÓDIGO

#include<stdio.h>
int main(){

    float numero;
    printf("Digite um número:");
    scanf("%f",&numero);

        if(numero > 80){
            printf("%2.f Número maior que 80\n", numero);
        }
        else if(numero < 25){
            printf("%2.f Número menor que 25\n", numero);
        }
        else if (numero == 40){
            printf("%2.f Número igual a 40\n", numero);
        }
        else{
            printf("Número inválido");
        }



    return 0;
}
