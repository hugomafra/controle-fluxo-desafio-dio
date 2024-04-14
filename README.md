# Desafio Controle de Fluxo 

 O desafio consiste em exercitar os conceitos de Controle de Fluxo em Java, criando um programa que recebe dois números `inteiros` como parâmetros e realiza a impressão dos números incrementados.

## Funcionalidade

O sistema recebe dois parâmetros via terminal, que representam dois números inteiros. Com esses números, o programa realiza a seguinte ação:

- Calcula a quantidade de iterações necessárias (usando um loop `for`) para imprimir cada interação.
 - Por exemplo, se os números 12 e 30 forem passados como parâmetros, o programa realizará 18 iterações para imprimir os números de 1 a 18, como: "Imprimindo o número 1", "Imprimindo o número 2" e assim por diante.

## Exceção Personalizada
Além disso, o programa trata a situação em que o *primeiro parâmetro é MAIOR que o segundo parâmetro*. Nesse caso, o programa lança uma exceção personalizada chamada `ParametrosInvalidosException` com a seguinte mensagem: *"O segundo parâmetro deve ser maior que o primeiro"*.

## Estrutura do Projeto
O projeto `Controle de Fluxo - Desafio` está estruturado da seguinte forma:

- `Contador.java`: Esta classe contém a lógica principal do programa, onde são realizados os cálculos e a impressão dos números incrementados.

- `ParametrosInvalidosException.java`: Esta classe representa a exceção customizada que é lançada quando os parâmetros são inválidos.

