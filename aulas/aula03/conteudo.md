# **Condicionais e Estruturas de Repetição em Python**

Em Python, usamos condicionais (`if`, `elif`, `else`) para executar diferentes blocos de código dependendo de uma condição. Já o `while` é utilizado para repetir um bloco de código enquanto uma condição for verdadeira. Vamos entender cada um deles com exemplos simples.

---

## **1. Estrutura `if` (Se...)**

A estrutura `if` é usada quando queremos executar um código apenas se uma condição for verdadeira.

### **Exemplo: Verificar se um número é positivo**

```python

numero = 10

if numero > 0:

print("O número é positivo.")

```

Se `numero` for maior que zero, a mensagem será exibida. Se não for, o código dentro do `if` será ignorado.

## **2. Estrutura `if...else` (Se...Senão...)**

O `else` é usado quando queremos definir um bloco de código para ser executado caso a condição do `if` não seja verdadeira.

### **Exemplo: Verificar se um número é positivo ou negativo**

```python

numero = -5

if numero > 0:

print("O número é positivo.")

else:

print("O número é negativo ou zero.")

```

Se `numero` for maior que 0, exibe "O número é positivo". Caso contrário, exibe "O número é negativo ou zero".

---

## **3. Estrutura `if...elif...else` (Se...Senão Se...Senão...)**

Se tivermos várias condições para verificar, usamos `elif` (abreviação de "else if").

### **Exemplo: Classificar uma nota escolar**

```python

nota = 7

if nota >= 7:

print("Aprovado!")

elif nota >= 5:

print("Recuperação.")

else:

print("Reprovado.")

```

- Se a nota for maior ou igual a 7 → "Aprovado!"

- Se a nota estiver entre 5 e 6.9 → "Recuperação."

- Se for menor que 5 → "Reprovado."

---

## **4. Estrutura `while` (Enquanto...)**

O `while` é usado para repetir um bloco de código enquanto uma condição for verdadeira.

### **Exemplo: Contagem regressiva**

```python

contador = 5

while contador > 0:

print(contador)

contador -= 1 # Diminui o valor do contador a cada repetição

print("Fim da contagem!")

```

Este código imprimirá os números de 5 até 1 e depois exibirá "Fim da contagem!".

---

### **Cuidado com loops infinitos!**

Se a condição do `while` nunca se tornar falsa, o programa pode entrar em um **loop infinito** e travar. Exemplo perigoso:

```python

x = 1

while x > 0: # Como x nunca diminui, esse loop nunca para!

print(x)

```

Sempre garanta que o valor de controle do `while` está sendo alterado corretamente dentro do laço.

---

## **Conclusão**

- `if` é usado para tomar decisões.

- `elif` permite testar múltiplas condições.

- `else` define um bloco para ser executado caso nenhuma condição seja atendida.

- `while` executa um bloco de código repetidamente enquanto a condição for verdadeira.

Essas estruturas são fundamentais para qualquer linguagem de programação.
