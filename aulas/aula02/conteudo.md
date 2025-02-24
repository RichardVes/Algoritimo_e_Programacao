# Aula02

## 1. O que são variáveis?

Variáveis são usadas para armazenar valores na memória do computador.
Em Python, não é necessário declarar o tipo da variável explicitamente.

### Tipos de Variáveis

Em Python, os principais tipos de variáveis são:

- `int` (números inteiros)
- `float` (números decimais)
- `str` (textos ou cadeias de caracteres)
- `bool` (valores booleanos: `True` ou `False`)

## 2. Criação de Variáveis

### Exemplo:

```python
numero_inteiro = 10
numero_decimal = 3.14
texto = "Python"
booleano = True
```

## Imprimindo na tela

Para exibir informações na tela, utilizamos a função `print()`.

### Exemplo:

```python
print("Olá, mundo!")
nome = "Alice"
print("Meu nome é", nome)
```

### Exercício 1:

Crie variáveis para armazenar seu nome, idade e cidade onde mora. Depois, imprima esses valores na tela.

---

### Exercício 2:

Crie uma variável para cada tipo de dado e use a função `type()` para verificar seu tipo.

```python
print(type(variavel))
```

---

## 3. Operações Aritméticas

Python suporta operações matemáticas básicas:

- `+` (adição)
- `-` (subtração)
- `*` (multiplicação)
- `/` (divisão)
- `//` (divisão inteira)
- `%` (módulo - resto da divisão)
- `**` (exponenciação)

### Exemplo:

```python
soma = 10 + 5
subtracao = 10 - 3
multiplicacao = 4 * 2
divisao = 10 / 2
divisao_inteira = 10 // 3
resto = 10 % 3
potencia = 2 ** 3
```

## 4. Pedindo entrada ao usuário

Para solicitar que o usuário insira um valor, utilizamos a função `input()`.

### Exemplo:

```python
nome = input("Digite seu nome: ")
idade = input("Digite sua idade: ")
print("Olá,", nome, "você tem", idade, "anos.")
```

### Exercício 3:

Peça para o usuário digitar seu nome e idade e imprima uma mensagem personalizada.

```python
# Seu código aqui
```

### Exercício 4:

Peça para o usuário digitar dois números e realize todas as operações matemáticas entre eles.

```python
# Seu código aqui
```

---

## 4. Operações Lógicas

As operações lógicas são usadas para comparações e retornam valores booleanos (`True` ou `False`).

- `==` (igualdade)
- `!=` (diferente)
- `>` (maior que)
- `<` (menor que)
- `>=` (maior ou igual a)
- `<=` (menor ou igual a)

### Exemplo:

```python
x = 10
y = 5

print(x == y)  # False
print(x > y)   # True
print(x != y)  # True
```

### Exercício 4:

Peça ao usuário para digitar sua idade e verifique se ele é maior de idade (18 anos ou mais).

```python
# Seu código aqui
```

--- FIM ---
