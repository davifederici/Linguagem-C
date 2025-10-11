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





                        SEGUNDO CÓDIGO

#include<stdio.h>
int main(){

    int numero;
    printf("Digite um número:");
    scanf("%d,&numero");

    if ( numero %10 == 0){
        printf("Número divísivel por 10\n", numero);
    }
    else if (numero %5 == 0){
        printf("Número divísivel por 5\n", numero);
    }
    else if (numero %2 == 0){
        printf("Número divísivel por 2\n", numero);
    }
    else{
        printf("Número não é divísivel por 2,5 e 10");
    }


    return 0;
}




                        TERCEIRO CÓDIGO

#include<stdio.h>
int main(){

    float x;
    printf("Digite o valor de x:");
    scanf("%f",&x);

    if (x > -10 && x <= 30){
        printf("%2.f Nùmero está no intervalo\n", x);
    }
    else{
        printf("Não está no intervalo");
    }
    return 0;
}




                        QUARTO CÓDIGO

#include<stdio.h>
int main(){
    int mes;
    printf("Digite o número do mês:");
    scanf("%d",&mes);

    switch(mes){
        case 1:
            printf("Mês de Janeiro");
            break;
        case 2:
            printf("Mês de fevereiro");
            break;
        case 3:
            printf("Mês de Março");
            break;
        case 4:
            printf("Mês de Abril");
            break;
        case 5:
            printf("Mês de Maio");
            break;
        case 6:
            printf("Mês de Junho");
            break;
        case 7:
            printf("Mês de JUlho");
            break;
        case 8:
            printf("Mês de Agosto");
            break;
        case 9:
            printf("Mês de Setembro");
            break;
        case 10:
            printf("Mês de Outubro");
            break;
        case 11:
            printf("Mês de Novembro ");
            break;
        case 12:
            printf("Mês de Dezembro");
            break;

        default:
        printf("Valor inválido \n");
        
    }
    return 0;
}




                        QUINTO CÓDIGO

#include<stdio.h>
int main(){

    float numero;
    printf("Digite um número:");
    scanf("%f",&numero);

    if (numero > 0){
        printf("%f Valor positivo\n", numero);
    }
    else{
        printf("%f Valor Negativo\n", numero);
    }

    float numero2;
    printf("Digite um número:");
    scanf("%f",&numero2);

    if (numero2 > 0){
        printf("%f Valor positivo\n", numero2);
    }
    else{
        printf("%f Valor Negativo\n", numero2);
    }

    float numero3;
    printf("Digite um número:");
    scanf("%f",&numero3);

    if (numero3 > 0){
        printf("%f Valor positivo\n", numero3);
    }
    else{
        printf("%f Valor Negativo\n", numero3);
    }

    float numero4;
    printf("Digite um número:");
    scanf("%f",&numero4);

    if (numero4 > 0){
        printf("%f Valor positivo\n", numero4);
    }
    else{
        printf("%f Valor Negativo\n", numero4);
    }

    float numero5;
    printf("Digite um número:");
    scanf("%f",&numero5);

    if (numero5 > 0){
        printf("%f Valor positivo\n", numero5);
    }
    else{
        printf("%f Valor Negativo\n", numero5);
    }

    return 0;
}




                        SEXTO CÓDIGO

