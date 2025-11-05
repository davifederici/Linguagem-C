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

#include<stdio.h>
int main(){

    int idade;
    printf("Informe sua idade:");
    scanf("%d",&idade);

    if (idade > 65){
        printf("Pessoa idosa\n",idade);
    }
    else if (idade > 19){
        printf("Maior de idade\n", idade);
    }
    else {
        printf("Menor de idade\n",idade);
    }

    return 0;
}




                        SÉTIMO CÓDIGO

#include<stdio.h>
int main(){

    int mes;
    printf("Digite um mês:");
    scanf("%d",&mes);

     switch(mes){
        case 1:
            printf("Este mês tem 31 dias");
            break;
        case 2:
            printf("Este mês tem 28 dias");
            break;
        case 3:
            printf("Este mês tem 31 dias");
            break;
        case 4:
            printf("Este mês tem 30 dias");
            break;
        case 5:
            printf("Este mês tem 31 dias");
            break;
        case 6:
            printf("Este mês tem 30 dias");
            break;
        case 7:
            printf("Este mês tem 31 dias");
            break;
        case 8:
            printf("Este mês tem 31 dias");
            break;
        case 9:
            printf("Este mês tem 30 dias");
            break;
        case 10:
            printf("Este mês tem 31 dias");
            break;
        case 11:
            printf("MEste mês tem 30 dias ");
            break;
        case 12:
            printf("Este mês tem 31 dias");
            break;

        default:
        printf("Valor inválido \n");
        
    }

    return 0;
}




                        OITAVO CÓDIGO

#include <stdio.h>

int main() {
    int codigo;
    float salario, reajuste, novo_salario;

    printf("Digite o código do cargo: ");
    scanf("%d", &codigo);

    printf("Digite o salário: ");
    scanf("%f", &salario);

    printf("\n--- Resultado ---\n");

    switch (codigo) {
        case 101:
            printf("Cargo: Gerente\n");
            printf("Salário: %.2f\n", salario);
            printf("Sem reajuste.\n");
            break;

        case 102:
            reajuste = salario * 0.005;
            novo_salario = salario + reajuste;
            printf("Cargo: Analista\n");
            printf("Salário base: %.2f\n", salario);
            printf("Reajuste: %.2f\n", reajuste);
            printf("Novo salário: %.2f\n", novo_salario);
            break;

        case 103:
            reajuste = salario * 0.015;
            novo_salario = salario + reajuste;
            printf("Cargo: Programador\n");
            printf("Salário base: %.2f\n", salario);
            printf("Reajuste: %.2f\n", reajuste);
            printf("Novo salário: %.2f\n", novo_salario);
            break;

        case 104:
            reajuste = salario * 0.03;
            novo_salario = salario + reajuste;
            printf("Cargo: Designer\n");
            printf("Salário base: %.2f\n", salario);
            printf("Reajuste: %.2f\n", reajuste);
            printf("Novo salário: %.2f\n", novo_salario);
            break;

        default:
            reajuste = salario * 0.40;
            novo_salario = salario + reajuste;
            printf("Cargo: Desconhecido\n");
            printf("Salário base: %.2f\n", salario);
            printf("Reajuste: %.2f\n", reajuste);
            printf("Novo salário: %.2f\n", novo_salario);
            break;
    }

    return 0;
}





                        NONO CÓDIGO

#include<stdio.h>
int main(){

    int a,b,c,area;
    printf("Escreva o lado A:");
    scanf("%d",&a);

    printf("Escreva o lado B:");
    scanf("%d",&b);

    printf("Escreva o lado C:");
    scanf("%d",&c);

    if (a + b > c){
         printf("%d e %d Formam um triângulo \n", a, b);
    }
    else{
        printf("Não formam um triângulo \n", c);
    }
    if (a + c > b){
        printf("%d e %d Formam um triângulo \n", a,c);
    }
    else {
        printf("Não formam um triângulo \n", b);
    }
    if (b + c > a){
        printf("%d e %d Formam um triângulo \n", b,c);
    }
    else{
        printf("Não formam um triângulo \n",a);
    }

    area = (a * (b + c)) / 2;
    printf("A area é: %d\n", area);

    return 0;

}




                        DÉCIMO CÓDIGO

#include<stdio.h>
int main(){

    int a,b,c,area;
    printf("Escreva o lado A:");
    scanf("%d",&a);

    printf("Escreva o lado B:");
    scanf("%d",&b);

    printf("Escreva o lado C:");
    scanf("%d",&c);

    if (a > 0 && b > 0 && c > 0){
        if (a == b && a == c && b == c ){
            printf("O triângulo é equilátero \n");
        }
        else if((a == b && a != c) || (a == c && a != b) || (b == c && b != a)){
            printf("O triângulo é isósceles\n");
        }
        else if (a != b && a != c && b != c){
            printf("O triângulo é escaleno\n");
        }
    } else {
        printf("Não formam triângulo\n");
    }


    return 0;

}




                        DÉCIMO PRIMEIRO CÓDIGO

#include<stdio.h>
int main(){

    int a,b;
    printf("Digite o valor de A:");
    scanf("%d",&a);

    printf("Digite o valor de B:");
    scanf("%d",&b);

    if (a%b==0 && b%a==0){
        printf("São Multiplos \n");
    }
    else{
        printf("Não são multiplos");
    }

    return 0;
}




                        DÉCIMO SEGUNDO CÓDIGO

#include<stdio.h>
int main(){

    float valor,prestacao;
    int parcelas;
    printf("Digite o valor da compra:");
    scanf("%f", &valor);

    if (valor <= 500){
        parcelas = 5;
    }
    else{
        parcelas = 8;
    }

    prestacao=valor/parcelas;

    printf("O valor será parcelado em %d de R$ %2.f cada\n", parcelas, prestacao);

    return 0;
}




                        DÉCIMO TERCEIRO CÓDIGO

#include<stdio.h>
int main(){

    float salario, vendas;
    printf("Digite o valor das vendas brutas da semana:R$");
    scanf("%f",&vendas);

    salario = 200 +(vendas*0.09);

    if (vendas > 1000){
        salario += 800;
    }
    printf("O salário total do vendedor será:R$%.2f\n",salario);

    return 0;
}





                        DÉCIMO QUARTO CÓDIGO

#include<stdio.h>
int main(){

    float valor, juros,prazo;
    printf("Digite o valor da compra?");
    scanf("%f",&valor);

    printf("Qual seria o prazo de pagamento?");
    scanf("%f",&prazo);

    if (prazo >= 1 && prazo <= 3){
        printf("O valor é de %.2f\n", valor);
    }
    else if (prazo >= 4 && prazo <= 7){
        juros = valor + 0.005;
        printf("O valor do juros é %.2f\n", juros);
    }
    else if(prazo >= 8 && prazo <= 12){
        juros = valor + 0.0015;
    }
    else if ( prazo >= 12 && prazo <= 20){
        juros = valor + 0.03;
        printf("O valor do juros é %.2f", juros);
    }
    else{
        printf("Prazo inválido!");
    }

    return 0;
}




                        DÉCIMO QUINTO CÓDIGO

#include <stdio.h>

int main() {
    float p1, p2, media;
    int faixa;

    printf("Digite a nota da primeira prova: ");
    scanf("%f", &p1);

    printf("Digite a nota da segunda prova: ");
    scanf("%f", &p2);

    media = (p1 + p2) / 2;

    faixa = (int) media;

    printf("Média: %.2f\n", media);

    switch (faixa) {
        case 0:
        case 1:
        case 2:
        case 3:
        case 4:
            printf("O conceito é D\n");
            break;

        case 5:
        case 6:
            printf("O conceito é C\n");
            break;

        case 7:
        case 8:
            printf("O conceito é B\n");
            break;

        case 9:
        case 10:
            printf("O conceito é A\n");
            break;

        default:
            printf("Erro: média fora do intervalo válido (0 a 10)\n");
    }

    return 0;
}





                        DÉCIMO SEXTO CÓDIGO

#include<stdio.h>
int fatorial(int n) {
    int fat = 1;
    for (int i = 1; i <= n; i++) {
        fat *= i;
    }
    return fat;
}

int main() {
    int numero;
    float f = 1.0;

    printf("Digite um número: ");
    scanf("%d", &numero);

    if (numero > 1 && numero < 5) {
        for (int i = 1; i <= numero; i++) {
            f += 1.0 / fatorial(i);
        }
        printf("O valor de F é: %.2f\n", f);
    } else {
        printf("Número inválido\n");
    }
    return 0;
}




                        DÉCIMO SÉTIMO CÓDIGO

#include<stdio.h>
int main(){

    int cpf,numerodp;
    float renda,imposto,desconto;
    printf("Digite seu CPF, o número de dependentes e a renda mensal:");
    scanf("%d %d %f", &cpf,&numerodp,&renda);

    desconto = renda * (numerodp* 0.005);

    if (renda > 7){
        imposto = renda * 0.020;
        printf("O valor líquido é %.2f", imposto);
    }
    else if (renda > 5) {
        imposto = renda * 0.015;
        printf("O valor líquido é %.2f", imposto); 
    }
    else if (renda > 3){
        imposto = renda * 0.010;
        printf("O valor líquido é %.2f", imposto);
    }
    else if (renda > 2){
        imposto = renda * 0.005;
        printf("O valor líquido é %.2f", imposto);
    }
    else{
        imposto = renda - 0;
        printf("O valor líquido é %.2f:", imposto);
    }
    

    return 0;
}




                        DÉCIMO OITAVO CÓDIGO

#include<stdio.h>
int main(){

    int a,b,i;
   
    printf("Digite o valor de A:");
    scanf("%d",&a);

    printf("Digite o valor de B:");
    scanf("%d",&b);

    if (a<=b){
        for(i=a;a<=b;i++){
        printf("%d\n",i);
        a++;
        }
    }
        else{
        printf("A maior que B");
        }

    return 0;
}




                        DÉCIMO NONO CÓDIGO

#include<stdio.h>
int main(){

    int a,b,i;
   
    printf("Digite o valor de A:");
    scanf("%d",&a);

    printf("Digite o valor de B:");
    scanf("%d",&b);

    if (a<=b){
        for(i=a;a<=b;i++){
        printf("%d\n",i);
        a++;
        }
    }
        else{
        printf("A maior que B");
        }

    return 0;
}




                        VIGÉSIMO CÓDIGO

#include<stdio.h>
int main(){

    int a,b,i;
   
    printf("Digite o valor de A:");
    scanf("%d",&a);

    printf("Digite o valor de B:");
    scanf("%d",&b);

    if (a<=b){
        printf("Os valores ímpares são:");
        for(i=a; i<=b; i++){
            if(i%2==1){
                printf("%d\n",i);
            }
        }
    }
        else{
            printf("Número inválido!");
        }

    return 0;
}




                        VIGÉSIMO PRIMEIRO CÓDIGO

#include<stdio.h>
int main(){

    int a,b,i;
   
    printf("Digite o valor de A:");
    scanf("%d",&a);

    printf("Digite o valor de B:");
    scanf("%d",&b);

    if (a<=b){
        printf("Os valores ímpares são:");
        for(i=a; i<=b; i++){
            if(i%2==1){
            printf("%d x %d\n",i,i*3);
            }
        }
    }
        else{
            printf("Número inválido!");
        }

    return 0;
}




                        VIGÉSIMO SEGUNDO CÓDIGO

#include<stdio.h>
int main(){

    int n,n1,i;
    printf("Digite o valor de N:");
    scanf("%d",&n);

    if(n > 0)
        for(i=0;i<=n;i++){
        printf("Digite o próximo número:");
        scanf("%d",&n1);
        printf("O triplo de %d é:%d\n",n1,n1*3);
    }
    else{
        printf("Valor inválido!");
    }

    return 0;
}




                        VIGÉSIMO TERCEIRO CÓDIGO

#include<stdio.h>
int main(){

    int n,n1,i,positivo=0,negativo=0;
    printf("Digite o valor de N:");
    scanf("%d",&n);

    if(n > 0)
        for(i=0;i<=n;i++){
        printf("Digite o próximo número:");
        scanf("%d",&n1);
            if(n1>0){
                positivo++;
            }
            else{
                negativo++;
            }
    }
    else{
        printf("Valor inválido!");
    }
    printf("%d são negativos e %d são positivos",positivo,negativo);

    return 0;
}




                        VIGÉSIMO QUARTO CÓDIGO

#include <stdio.h>

int main() {
    int valor, soma = 0, contador = 0;
    float media;

    printf("Digite valores positivos (um número negativo encerra a leitura):\n");

    while (1) { 
        scanf("%d", &valor);

        if (valor < 0) { 
            break;
        }

        soma += valor;   
        contador++;      
    }

    if (contador > 0) { 
        media = (float)soma / contador;
        printf("A média dos valores é: %.2f\n", media);
    } else {
        printf("Nenhum valor positivo foi digitado.\n");
    }

    return 0;
}





                        VIGÉSIMO QUINTO CÓDIGO

#include <stdio.h>

int main() {
    int valor, soma = 0, contador = 0;
    float media;

    printf("Digite números (0 encerra a leitura):\n");

    while (1) {
        scanf("%d", &valor);

        if (valor == 0) { // encerra a leitura
            break;
        }

        if (valor % 2 == 0) { // verifica se é par
            soma += valor;
            contador++;
        }
    }

    if (contador > 0) {
        media = (float)soma / contador;
        printf("A média dos números pares é: %.2f\n", media);
    } else {
        printf("Nenhum número par foi digitado.\n");
    }

    return 0;
}





                        VIGÉSIMO SEXTO CÓDIGO
            
#include <stdio.h>

int main() {
    int i, valor, maior, menor;
    printf("Digite 50 valores inteiros:\n");
    scanf("%d", &valor);
    maior = valor;
    menor = valor;

    for (i = 1; i < 50; i++) {
        scanf("%d", &valor);

        if (valor > maior) {
            maior = valor;
        }
        if (valor < menor) {
            menor = valor;
        }
    }

    printf("O maior valor digitado foi: %d\n", maior);
    printf("O menor valor digitado foi: %d\n", menor);

    return 0;
}







                        VIGÉSIMO SÉTIMO CÓDIGO

#include <stdio.h>

int main() {
    int n, i, valor, soma = 0, maior, menor;
    float media;

    printf("Quantos números deseja digitar? ");
    scanf("%d", &n);

    if (n < 3) {
        printf("Erro: é necessário digitar pelo menos 3 números.\n");
        return 0;
    }

    printf("Digite %d números inteiros:\n", n);
    scanf("%d", &valor);

    soma = valor;
    maior = valor;
    menor = valor;

    for (i = 1; i < n; i++) {
        scanf("%d", &valor);
        soma += valor;

        if (valor > maior)
            maior = valor;

        if (valor < menor)
            menor = valor;
    }

    soma = soma - maior - menor;

    media = (float)soma / (n - 2);

    printf("A média excluindo o maior (%d) e o menor (%d) é: %.2f\n", maior, menor, media);

    return 0;
}





                        VIGÉSIMO OITAVO CÓDIGO

#include <stdio.h>

int main() {
    int celsius;         // variável para o valor em Celsius
    float fahrenheit;    // variável para o valor convertido em Fahrenheit

    printf("Tabela de conversão de Celsius para Fahrenheit\n");
    printf("-------------------------------------------------\n");
    printf(" Celsius\tFahrenheit\n");
    printf("-------------------------------------------------\n");

    for (celsius = -100; celsius <= 100; celsius += 5) {
        fahrenheit = (9.0 / 5.0) * celsius + 32;  // fórmula de conversão
        printf(" %7d\t%10.2f\n", celsius, fahrenheit);
    }

    printf("-------------------------------------------------\n");

    return 0;
}





                        VIGÉSIMO NONO CÓDIGO

#include <stdio.h>

int main() {
    int numerador, denominador;
    float S = 0;

    numerador = 1;

    for (denominador = 1; denominador <= 50; denominador++) {
        S += (float)numerador / denominador;
        numerador += 2;
    }

    printf("O valor de S é: %.2f\n", S);

    return 0;
}






                        TRIGÉSIMO CÓDIGO

#include <stdio.h>
#include <math.h> 

int main() {
    int i, denominador;
    float s = 0, termo;  

    denominador = 50;

    for (i = 1; i <= 50; i++) {
        termo = (float)pow(2, i) / denominador;  
        s += termo;
        denominador--; 
    }

    printf("O valor de S é: %.2f\n", s);

    return 0;
}




                        TRIGÉSIMO PRIMEIRO CÓDIGO

#include <stdio.h>

int main() {
    int n, i;
    int produto = 1;  // inicializa com 1, pois é o elemento neutro da multiplicação

    printf("Digite um número: ");
    scanf("%d", &n);

    printf("Números: ");
    for (i = 1; i <= n; i++) {
        printf("%d ", i);
        produto *= i;  // multiplica o produto pelos números de 1 até n
    }

    printf("\nProduto: %d\n", produto);

    return 0;
}





                        TRIGÉSIMO SEGUNDO CÓDIGO

#include <stdio.h>

int main() {
    int n, i;
    int fatorial = 1;

    printf("Digite um número inteiro: ");
    scanf("%d", &n);

    if (n < 0) {
        printf("Não existe fatorial de número negativo.\n");
    } else {
        for (i = 1; i <= n; i++) {
            fatorial *= i;
        }
        printf("O fatorial de %d é: %d\n", n, fatorial);
    }

    return 0;
}





                        TRIGÉSIMO TERCEIRO CÓDIGO

#include <stdio.h>

int main() {
    int n, i, j;
    float s = 1.0, fatorial;

    printf("Digite um valor inteiro e positivo: ");
    scanf("%d", &n);

    if (n < 0) {
        printf("Erro: o número deve ser positivo.\n");
        return 0;
    }

    for (i = 1; i <= n; i++) {
        fatorial = 1;
        for (j = 1; j <= i; j++) {
            fatorial *= j;
        }
        s += 1.0 / fatorial;
    }

    printf("O valor de S é: %.6f\n", s);

    return 0;
}





                        TRIGÉSIMO QUARTO CÓDIGO

#include <stdio.h>

int main() {
    float salario, somaSalario = 0, maiorSalario = 0;
    int filhos, totalPessoas = 0, somaFilhos = 0, contAte100 = 0;
    float mediaSalario, mediaFilhos, percentual;

    while (1) {
        printf("Digite o salário (negativo para encerrar): ");
        scanf("%f", &salario);

        if (salario < 0) {
            break; // encerra a leitura
        }

        printf("Digite o número de filhos: ");
        scanf("%d", &filhos);

        somaSalario += salario;
        somaFilhos += filhos;
        totalPessoas++;

        if (salario > maiorSalario) {
            maiorSalario = salario;
        }

        if (salario <= 100) {
            contAte100++;
        }
    }

    if (totalPessoas > 0) {
        mediaSalario = somaSalario / totalPessoas;
        mediaFilhos = (float)somaFilhos / totalPessoas;
        percentual = (float)contAte100 / totalPessoas * 100;

        printf("\n--- RESULTADOS ---\n");
        printf("a) Média do salário da população: R$ %.2f\n", mediaSalario);
        printf("b) Média do número de filhos: %.2f\n", mediaFilhos);
        printf("c) Maior salário: R$ %.2f\n", maiorSalario);
        printf("d) Percentual de pessoas com salário até R$100,00: %.2f%%\n", percentual);
    } else {
        printf("Nenhum dado foi informado.\n");
    }

    return 0;
}





                        TRIGÉSIMO QUINTO CÓDIGO

#include <stdio.h>

int main() {
    int codigo, cont = 0;
    float preco, novoPreco;
    float somaPreco = 0, somaNovoPreco = 0;

    printf("Digite o código e o preço de custo (código negativo encerra):\n");

    while (1) {
        printf("\nCódigo do produto: ");
        scanf("%d", &codigo);

        if (codigo < 0) {
            break; // encerra a leitura
        }

        printf("Preço de custo: R$ ");
        scanf("%f", &preco);

        novoPreco = preco * 1.20; // aumento de 20%

        printf("Produto %d - Novo preço: R$ %.2f\n", codigo, novoPreco);

        somaPreco += preco;
        somaNovoPreco += novoPreco;
        cont++;
    }

    if (cont > 0) {
        float mediaPreco = somaPreco / cont;
        float mediaNovoPreco = somaNovoPreco / cont;

        printf("\n--- RESUMO ---\n");
        printf("Média dos preços SEM aumento: R$ %.2f\n", mediaPreco);
        printf("Média dos preços COM aumento: R$ %.2f\n", mediaNovoPreco);
    } else {
        printf("\nNenhum produto foi informado.\n");
    }

    return 0;
}




                        TRIGÉSIMO SEXTO CÓDIGO

#include<stdio.h>
int main(){

    int i, vetA[6], neg=0,pos=0;

    printf("Digite 6 valores:\n");
    for(i=0;i<6;i++){
        scanf("%d", &vetA[i]);
    }
    for(i=0;i<6;i++){
        if (vetA[i]<0){
            neg++;
        }
        else{
            pos++;
        }
    }

    printf("\nOs valores negativos são:%d", neg);
    printf("\nOs valores positivos são:%d", pos);

    return 0;
}




                        TRIGÉSIMO SÉTIMO CÓDIGO

#include <stdio.h>

int main() {
    int teste1[10], teste2[10], i;


    printf("Digite 10 valores inteiros:\n");
    for(i = 0; i < 10; i++) {
        scanf("%d", &teste1[i]);
    }


    for(i = 0; i < 10; i++) {
        if(i % 2 == 0) {  
            teste2[i] = teste1[i] * 5;
        } else {        
            teste2[i] = teste1[i] + 5;
        }
    }

    
    printf("\nVetor teste1:\n");
    for(i = 0; i < 10; i++) {
        printf("%d ", teste1[i]);
    }

    printf("\n\nVetor teste2:\n");
    for(i = 0; i < 10; i++) {
        printf("%d ", teste2[i]);
    }

    printf("\n");
    return 0;
}





                        TRIGÉSIMO OITAVO CÓDIGO

#include <stdio.h>
int main() {

    int A[10], i;

    printf("\nDigite 10 valores: ");
    for (i = 0; i < 10; i++) {
        scanf("%d", &A[i]);
    }

    printf("\nValores menores ou iguais a 10:\n");
    for (i = 0; i < 10; i++) {
        if (A[i] <= 10) {
            printf("%d ", A[i]);
        }
    }

    return 0;
}





                        TRIGÉSIMO NONO CÓDIGO

