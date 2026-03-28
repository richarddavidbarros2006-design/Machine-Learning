# 📘 Resumo — Primeiros Conceitos de Programação em Python

## 🎯 Objetivo
Apresentar os conceitos iniciais da linguagem Python, permitindo a criação dos primeiros programas e a compreensão da lógica básica de programação.

---

## 🧱 Estrutura Básica de um Programa

- Execução sequencial (de cima para baixo)
- Não exige função principal (`main`)

### Exemplo:
print("Meu primeiro programa em Python")

---

## 💬 Comentários

Comentários são usados para explicar o código e não são executados.

### ✔️ Uma linha:
# Este é um comentário

### ✔️ Múltiplas linhas (docstring):
"""
Comentário de várias linhas
"""

---

## 📦 Variáveis

Variáveis armazenam valores na memória.

### Características:
- Não precisam de declaração de tipo
- Tipagem dinâmica
- Podem mudar de valor

### Exemplo:
nome = "Ana"
idade = 20
altura = 1.65

---

## 🔢 Tipos de Dados Básicos

| Tipo | Descrição | Exemplo |
|------|----------|--------|
| int | Números inteiros | 10 |
| float | Números decimais | 19.90 |
| str | Texto | "Python" |
| bool | Verdadeiro/Falso | True |

---

## 🔍 Função `type()`

Permite verificar o tipo de uma variável:

print(type(idade))  
print(type(preco))

---

## ⌨️ Entrada de Dados

A função `input()` permite receber dados do usuário:

nome = input("Digite seu nome: ")

⚠️ Todo valor recebido é do tipo `str`

---

## 🔄 Conversão de Tipos (Casting)

Necessária para trabalhar com números:

idade = int(input("Digite sua idade: "))  
altura = float(input("Digite sua altura: "))

---

## ➗ Operadores Aritméticos

| Operador | Função |
|----------|--------|
| + | Soma |
| - | Subtração |
| * | Multiplicação |
| / | Divisão |
| // | Divisão inteira |
| % | Resto |
| ** | Potência |

### Exemplo:
a = 10  
b = 3  

print(a + b)  
print(a * b)  
print(a ** b)  

---

## 🧠 Boas Práticas

- Use nomes descritivos  
- Evite acentos e espaços  
- Utilize `snake_case`  
- Mantenha padrão no código  

### Exemplo:
media_final = 7.5  
total_alunos = 30  

---

## 📝 Exercícios Propostos

1. Solicitar nome e idade e exibir mensagem personalizada  
2. Ler dois números e mostrar a soma  
3. Calcular a média de três notas  

---

## 📎 Conclusão

Este módulo apresenta os fundamentos essenciais da programação em Python, incluindo variáveis, tipos de dados, entrada de dados e operações básicas, formando a base para o aprendizado de estruturas mais avançadas.
