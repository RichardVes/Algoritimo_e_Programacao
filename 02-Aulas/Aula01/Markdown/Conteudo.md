# Introdução a Algoritmos em Python

---

## 1. O que é um Algoritmo?

### Definição:

    Um algoritmo é uma sequência finita de instruções que resolvem um problema.
    Exemplo simples: Fazer café (explicar passo a passo).

## Diferença entre Algoritmo e Código

    Algoritmos são independentes da linguagem de programação, enquanto o código é a implementação em uma linguagem específica.
    Apresentar como a mesma ideia de algoritmo pode ser escrita em diferentes linguagens (exemplo: Python e pseudocódigo).

---

## 2. Python como Linguagem para Algoritmos

### Introdução à linguagem Python, Variáveis e Tipos de Dados em Python

## O que são Variáveis?

    Definição:
    Variáveis são como "caixinhas" onde podemos armazenar informações que serão usadas ao longo do programa.

    Objetivo:
    Permitem que os dados sejam armazenados, manipulados e processados.

    Exemplo simples:
    Imagine que queremos guardar a idade de uma pessoa.
    Podemos usar uma variável chamada idade e armazenar o valor 25 nela.

### Como Criar Variáveis em Python?

    Em Python, não é necessário declarar o tipo da variável antes de usá-la.
    Basta atribuir um valor à variável, e o Python automaticamente decide o tipo de dado da variável com base no valor atribuído.

```python
nome = "João"  # A variável 'nome' será do tipo string
altura = 1.75   # A variável 'altura' será do tipo float
```

---

## 3. Principais Tipos de Dados em Python

### Inteiros (int)

    Usados para armazenar números inteiros (sem casas decimais).

> Exemplos: 3, -5, 1000

```python
idade = 25
saldo = -500
print(type(idade))  # Saída: <class 'int'>
```

### Ponto flutuante (float)

    Usados para armazenar números com casas decimais.

> Exemplos: 3.14, -1.5, 2.0

```python
pi = 3.14
temperatura = -2.5
print(type(pi))  # Saída: <class 'float'>
```

### Strings (str)

    Usadas para armazenar texto (sequências de caracteres).

> Exemplos: "João", "Python", "Olá, Mundo!"

```python
nome = "Maria"
saudacao = "Olá, " + nome
print(saudacao)  # Saída: Olá, Maria
print(type(nome))  # Saída: <class 'str'>
```

### Booleanos (bool)

    Usados para armazenar valores de verdadeiro ou falso.

> Exemplos: True, False

```python
is_adulto = True
is_maior_de_idade = 18 > 21  # False
print(is_adulto)  # Saída: True
print(type(is_adulto))  # Saída: <class 'bool'>
```

--- FIM ---
