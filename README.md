# azure-RecursosCopilot  

Este projeto faz parte da **Prática 3** do curso **Serviços Cloud com foco em IA: Explorando os Recursos de IA Generativa com Copilot e OpenAI**.  

## 📌 Descrição  
O projeto explora a utilização do **Chat Copilot**, permitindo a interação com IA para obter respostas textuais, gerar imagens e até criar códigos.  

## 📥 Inputs  
Solicitações enviadas para o Chat Copilot:  
1. **Me indique os melhores destinos de viagem no Nordeste do Brasil.**  
2. **Gere uma imagem de um casal viajando nos Lençóis Maranhenses (MA).**  
3. **Faça um código simples de uma calculadora usando a linguagem C.**  

## 📤 Outputs  
### 1️⃣ Melhores destinos de viagem no Nordeste do Brasil  
O Nordeste do Brasil é um verdadeiro paraíso com destinos incríveis! Aqui estão alguns dos melhores lugares para visitar:  

- **Fernando de Noronha (PE):** Um arquipélago paradisíaco com praias de águas cristalinas, perfeito para mergulho e contato com a natureza.  
- **Lençóis Maranhenses (MA):** Dunas e lagoas de água doce que formam um cenário único no mundo.  
- **Porto de Galinhas (PE):** Famoso por suas piscinas naturais e praias de areia branca.  
- **Jericoacoara (CE):** Conhecida como "Jeri", oferece lagoas de água doce, dunas e um pôr do sol espetacular.  
- **Chapada Diamantina (BA):** Ideal para quem ama ecoturismo, com cachoeiras, grutas e trilhas incríveis.  
- **Maceió (AL):** Praias urbanas e piscinas naturais que encantam qualquer visitante.  

Esses destinos combinam **beleza natural, cultura rica e hospitalidade calorosa**. Qual deles chamou mais a sua atenção? 😊  

### 2️⃣ Geração de imagem  
_Imagem de um casal viajando nos Lençóis Maranhenses (MA) gerada pela IA:_  
![um casal viajando nos lençóis maranhenses (1)](https://github.com/user-attachments/assets/2bc58b33-6877-4d87-bb86-c525a88d668c)
  

### 3️⃣ Código da calculadora em C  
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

## 💡 Insights obtidos com o projeto  
- **Exploração prática** do potencial da IA generativa aplicada a diferentes tipos de solicitações.  
- **Compreensão das respostas geradas** pelo Chat Copilot, analisando a precisão e relevância das informações fornecidas.  
- **Integração de diferentes tipos de outputs** (texto, imagem e código) em um único fluxo de interação com IA.  
- **Possibilidades de aprimoramento** para interações mais avançadas e personalizadas com a IA.  
