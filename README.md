# Controle de Fluxo - Desafio 
## Trilha JAVA Básico | DIO

Como desafio foi proposto um exercicio a partir do seguinte enunciado:

### Vamos exercitar todo o conteúdo apresentado no módulo de Controle de Fluxo codificando o seguinte cenário:

O sistema deverá receber dois parâmetros via terminal que representarão dois números inteiros, com estes dois números você deverá obter a quantidade de interações `(for)` e realizar a impressão no console `(System.out.print)` dos números incrementados, exemplo:

- Se você passar os números 12 e 30, logo teremos uma interação `(for)` com 18 ocorrências para imprimir os números, exemplo: `"Imprimindo o número 1"`, `"Imprimindo o número 2"` e assim por diante.
- Se o primeiro parâmetro for MAIOR que o segundo parâmetro, você deverá lançar a exceção customizada chamada de `ParametrosInvalidosException` com a segunda mensagem: `"O segundo parâmetro deve ser maior que o primeiro"`

1. Crie o projeto `DesafioControleFluxo`
2. Dentro do projeto, crie a classe `Contador.java` para realizar toda a codificação do nosso programa.
3. Dentro do projeto, crie a classe `ParametrosInvalidosException` que representará a exceção de negócio no sistema.

## Status do Projeto:
### Concluído.

## Features
- Entrada Interativa: O programa solicita ao usuário dois números inteiros como entrada e faz uma contagem baseada nesses parâmetros.
- Validação de Parâmetros: Se o segundo parâmetro fornecido for menor que o primeiro, o programa lança uma exceção customizada `(ParametrosInvalidosException)`, garantindo que a contagem só ocorra se os valores forem válidos.
- Exceção Customizada: Implementação de uma exceção personalizada chamada `ParametrosInvalidosException`, que exibe uma mensagem de erro clara e objetiva ao usuário, caso os parâmetros estejam incorretos.
- Contagem Progressiva: O programa imprime uma sequência de números incrementais a partir da diferença entre os parâmetros, fornecendo feedback visual em cada iteração da contagem.
- Fácil Extensão: O código pode ser facilmente estendido para incluir novas funcionalidades ou alterar o comportamento da contagem.

## Pré-requisitos e como rodar a aplicação
É uma aplicação JAVA simples, para rodar deve ser ultilizado alguma IDE com suporte a linguagem JAVA, como IntelliJ, Eclipse, etc.

## Tecnologias
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

## Autor
### Feito por Thiago Piassi

[![Linkedin Badge](https://img.shields.io/badge/-Thiago-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/thiagopiassi/)](https://www.linkedin.com/in/thiagopiassi/) 

