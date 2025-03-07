Claro! Aqui está um exemplo simples de uma calculadora em C que realiza as quatro operações básicas: adição, subtração, multiplicação e divisão.

```c
#include <stdio.h>

int main() {
    char operacao;
    double num1, num2, resultado;

    printf("Escolha uma operação (+, -, *, /): ");
    scanf(" %c", &operacao);

    printf("Digite o primeiro número: ");
    scanf("%lf", &num1);

    printf("Digite o segundo número: ");
    scanf("%lf", &num2);

    switch (operacao) {
        case '+':
            resultado = num1 + num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '-':
            resultado = num1 - num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '*':
            resultado = num1 * num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '/':
            if (num2 != 0) {
                resultado = num1 / num2;
                printf("Resultado: %.2lf\n", resultado);
            } else {
                printf("Erro: Divisão por zero!\n");
            }
            break;
        default:
            printf("Operação inválida!\n");
    }

    return 0;
}
```

Esse código solicita ao usuário que escolha uma operação e insira dois números. Dependendo da operação escolhida, ele executa o cálculo correspondente. Experimente compilar e rodar este código para ver como funciona! 😊 Se precisar de algo mais, é só pedir.