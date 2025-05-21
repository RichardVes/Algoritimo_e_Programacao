# Aula: Comando `for` em Python

## 🎯 Objetivo

Compreender o funcionamento do laço de repetição `for` em Python, aplicando-o em situações práticas para percorrer sequências como listas, strings e intervalos numéricos.

---

## 🧠 O que é o `for`?

O `for` é uma estrutura de repetição (ou laço) usada para iterar sobre elementos de uma sequência, como listas, tuplas, strings ou objetos gerados pela função `range()`.

Sua sintaxe básica é:

```python
for variavel in sequencia:
    # bloco de código
```

A cada iteração, a variável recebe um valor da sequência, e o bloco de código é executado.

---

## ✅ Exemplos

### 1. Iterando sobre uma lista

```python
frutas = ["maçã", "banana", "laranja"]

for fruta in frutas:
    print(fruta)
```

### 2. Iterando sobre uma string

```python
palavra = "Python"

for letra in palavra:
    print(letra)
```

### 3. Usando `range()` para criar uma sequência de números

```python
for i in range(5):
    print(i)
```

> Saída:  
> 0  
> 1  
> 2  
> 3  
> 4

### 4. Range com início, fim e passo

```python
for i in range(1, 10, 2):
    print(i)
```

> Saída:  
> 1  
> 3  
> 5  
> 7  
> 9

---

## 🧪 Exercícios

### Exercício 1

Escreva um programa que imprima os números de 1 a 10 usando `for`.

### Exercício 2

Escreva um programa que conte quantas vogais há na string `"Programação"`.

### Exercício 3

Utilizando `range()`, escreva um programa que imprima os números pares de 0 a 20.

---

## 🔄 Dica: Função `enumerate()`

Se quiser saber o índice de cada item durante a iteração, use a função `enumerate()`:

```python
nomes = ["Carlos", "Beatriz", "Lucas"]

for i, nome in enumerate(nomes):
    print(f"{i}: {nome}")
```

---

## 📌 Conclusão

O `for` é uma ferramenta poderosa para percorrer elementos de coleções e executar blocos de código repetidamente. Entender seu funcionamento é essencial para o desenvolvimento em Python.

---
