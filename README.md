# Calculadora em Java

## Autor
Renan Felix

## Data de Lançamento
08/11/2023

## Versão
1.01

## Descrição
Este é um projeto de calculadora desenvolvido em Java. A calculadora oferece funcionalidades para realizar operações matemáticas básicas, como adição, subtração, multiplicação e divisão.

## Funcionalidades
A calculadora possui os seguintes recursos:

- Adição de dois números
- Subtração de dois números
- Multiplicação de dois números
- Divisão de dois números

## Uso
Para utilizar a calculadora, siga os passos abaixo:

1. Instale o Java em seu sistema, se ainda não estiver instalado.

2. Clone o repositório do projeto

3. Navegue até a pasta do projeto:

4. Compile o código-fonte:

5. Execute a calculadora:

Agora você pode interagir com a calculadora no terminal e realizar operações matemáticas.

## Classe Calculadora

A classe `Calculadora` é a principal do projeto e contém os seguintes métodos:

- `soma(double a, double b)`: Realiza a adição de dois números e retorna o resultado.
- `subtracao(double a, double b)`: Realiza a subtração de dois números e retorna o resultado.
- `multiplicacao(double a, double b)`: Realiza a multiplicação de dois números e retorna o resultado.
- `divisao(double a, double b)`: Realiza a divisão de dois números e retorna o resultado.

### Exemplo de Uso

```java
Calculadora calculadora = new Calculadora();
double resultado = calculadora.soma(5.0, 3.0);
System.out.println("5 + 3 = " + resultado);

