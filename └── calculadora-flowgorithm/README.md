# Calculadora Universal

## Aluno
**Natanael Ribeiro da Cruz**

## Objetivo do Programa

O objetivo deste programa é desenvolver, em Flowgorithm, uma calculadora multifuncional que reúna, em um único menu interativo, diversas operações matemáticas e de conversão de uso cotidiano — desde cálculos de saúde (IMC) e geometria (áreas) até finanças (juros e desconto), estatística básica (média) e trigonometria. A proposta é consolidar, em um só projeto, conceitos de estruturas de decisão (`if`/`else`), estruturas de repetição (`while`) e validação de entrada de dados.

## Descrição do Funcionamento

Ao ser executado, o programa exibe um menu principal com 13 categorias de cálculo, numeradas de 1 a 13, além da opção **[0] Sair**, que encerra a execução.

O usuário digita o número correspondente à calculadora desejada. Caso o valor informado seja inválido (fora do intervalo permitido), o programa exibe uma mensagem de erro e solicita uma nova entrada, repetindo esse processo até que uma opção válida seja informada.

Após a escolha, o programa solicita os dados necessários para aquele cálculo específico (por exemplo, peso e altura para o IMC, ou base e altura para a área de um triângulo), realiza o processamento e exibe o resultado formatado na tela, geralmente com duas ou quatro casas decimais. Alguns módulos, como Tabuada, Temperatura, Conversor de Unidades e Trigonometria, possuem submenus próprios, permitindo ao usuário escolher entre diferentes operações dentro daquela categoria.

## Funções Implementadas (20)

| # | Função | Descrição |
|---|--------|-----------|
| 1 | **Cálculo de IMC** | Calcula o Índice de Massa Corporal a partir do peso e da altura e classifica o resultado (abaixo do peso, peso normal, excesso de peso, obesidade graus I, II ou mórbida). |
| 2 | **Área do Quadrado** | Calcula a área a partir da medida do lado. |
| 3 | **Área do Triângulo** | Calcula a área a partir da base e da altura. |
| 4 | **Área do Círculo** | Calcula a área a partir do raio. |
| 5 | **Área do Losango** | Calcula a área a partir das diagonais maior e menor. |
| 6 | **Soma** | Soma dois números informados pelo usuário. |
| 7 | **Subtração** | Subtrai dois números informados pelo usuário. |
| 8 | **Multiplicação** | Multiplica dois números informados pelo usuário. |
| 9 | **Divisão** | Divide dois números informados pelo usuário. |
| 10 | **Potência** | Calcula um número elevado a um expoente informado. |
| 11 | **Par ou Ímpar** | Verifica se um número inteiro informado é par ou ímpar. |
| 12 | **Comparação entre Valores** | Compara dois valores e informa qual é maior, menor ou se são iguais. |
| 13 | **Média Aritmética** | Calcula a média de três notas informadas. |
| 14 | **Porcentagem** | Calcula o percentual de um valor informado. |
| 15 | **Regra de Três Simples** | Resolve uma regra de três simples a partir de três valores conhecidos. |
| 16 | **Juros Simples** | Calcula o valor dos juros e o montante final a partir de capital, taxa e tempo. |
| 17 | **Desconto** | Calcula o valor do desconto e o preço final a partir do preço original e do percentual de desconto. |
| 18 | **Conversão de Temperatura** | Converte temperaturas entre Celsius e Fahrenheit (nos dois sentidos). |
| 19 | **Conversor de Unidades** | Converte unidades de comprimento, área, volume, massa e capacidade. |
| 20 | **Trigonometria** | Calcula seno, cosseno ou tangente de um ângulo informado em graus. |

## Funções Obrigatórias

Conforme exigido pela atividade, o programa contempla as seguintes funções obrigatórias:

- ✅ **Cálculo de IMC** — Opção **[1]** do menu principal.
- ✅ **Cálculo de Área** — Opção **[2]** do menu principal, com suporte a quatro figuras geométricas (quadrado, triângulo, círculo e losango).

## Instruções para Execução

1. Instale o **Flowgorithm** (disponível em [flowgorithm.org](http://www.flowgorithm.org)), caso ainda não o possua.
2. Abra o arquivo `Calculadora_Universal.fprg` no Flowgorithm.
3. Clique em **Execute** (ou pressione **F5**) para rodar o fluxograma.
4. No menu exibido, digite o número correspondente à calculadora desejada e pressione **Enter**.
5. Siga as instruções apresentadas na tela para inserir os dados solicitados.
6. Para encerrar o programa a qualquer momento no menu principal, digite **0**.

---
*Projeto desenvolvido em Flowgorithm como parte de atividade acadêmica.*
