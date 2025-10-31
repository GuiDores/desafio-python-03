# desafio-python-03
# ➕ Calculadora Simples de Soma

Este é o terceiro projeto na minha jornada de aprendizado em Python. O foco aqui foi consolidar a entrada de dados do usuário e realizar uma operação aritmética básica.

## 🎯 Objetivo do Projeto

O objetivo deste script é demonstrar a capacidade do Python de:

1.  Receber dois valores numéricos do usuário.
2.  Garantir que as entradas sejam tratadas como números inteiros (`int`).
3.  Realizar a operação de soma (`+`).
4.  Exibir o resultado em um formato claro.

## 💻 Código-Fonte

```python
num1 = int(input('Digite um numero: '));
num2 = int(input('Digite outro numero: '));
soma = num1 + num2;
print(num1, '+', num2, '=', soma);
