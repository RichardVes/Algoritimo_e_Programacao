# 🐍 Aula: Estrutura de Repetição Condicional `while` em Python

## Objetivos da Aula

- Compreender o funcionamento da estrutura de repetição `while`
- Aprender a criar laços de repetição com condição lógica
- Praticar a criação de algoritmos que utilizem o `while` para resolver problemas reais

---

## 📚 Introdução

A estrutura `while` é utilizada para repetir um bloco de código **enquanto uma condição for verdadeira**. Quando a condição deixa de ser verdadeira, a execução do laço é encerrada.

### Sintaxe básica:

```python
while condição:
    # bloco de código
```

## Exemplo 1: Contando de 1 a 5
contador = 1
while contador <= 5:
    print(contador)
    contador += 1

>>Saída:
1
2
3
4
5

## Atenção: Loop Infinito
Um erro comum é esquecer de atualizar a variável de controle, o que pode causar loop infinito:
x = 1
while x <= 5:
    print(x)
>> nunca termina!


## Estrutura de Controle com break e continue
break - interrompe o laço
```
while True:
    valor = int(input("Digite um número (0 para sair): "))
    if valor == 0:
        break
    print(f"Você digitou: {valor}")
```
## continue - pula para a próxima iteração
```
i = 0
while i < 10:
    i += 1
    if i % 2 == 0:
        continue
    print(i)  # imprime apenas números ímpares
```


#Exercícios Práticos
Exercício 1
Escreva um programa que imprime os números de 1 a 10 utilizando o laço while.

Exercício 2
Crie um programa que solicita números ao usuário até que ele digite zero. No final, mostre a soma de todos os números digitados (excluindo o zero).

Exercício 3
Crie um contador regressivo de 10 até 1 usando while.

Exercício 4
Peça ao usuário para digitar uma senha. Enquanto a senha não for "1234", continue pedindo. Quando estiver correta, exiba "Acesso permitido".

Exercício 5
Escreva um programa que calcule a média de vários números digitados pelo usuário. A leitura deve parar quando o usuário digitar -1.

Exercício 6
Faça um programa que simule um caixa eletrônico. O usuário pode sacar valores até acabar o saldo. Quando o saldo for zero, encerre o programa com a mensagem "Saldo insuficiente".

Exercício 7
Escreva um programa que imprime todos os números pares de 0 a 50 usando while.

Exercício 8
Crie um programa que simule uma senha com 3 tentativas. Após a terceira tentativa incorreta, exiba "Acesso bloqueado".

Exercício 9
Escreva um jogo de adivinhação. O programa escolhe um número aleatório entre 1 e 100 e o usuário tenta adivinhar. O laço continua até o usuário acertar.

Exercício 10
Simule uma calculadora que repete as operações até que o usuário escolha a opção de sair.
```
