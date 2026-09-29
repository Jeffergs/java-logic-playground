# 📖 Sintaxe do Pseudocódigo

> Referência rápida da sintaxe utilizada nos exercícios de pseudocódigo.

## 🎯 Objetivo

Aprender uma notação simples para representar algoritmos sem depender da sintaxe de uma linguagem de programação.

O pseudocódigo será utilizado apenas para **expressar a lógica da solução**.

---

## 🟢 Estrutura básica

Todo algoritmo pode ser representado entre `Início` e `Fim`.

```text
Início

    // passos do algoritmo

Fim
```

---

## 📥 Entrada

Utilizamos `Leia` para representar uma entrada de dados.

```text
Leia nome
Leia idade
Leia salario
```

Exemplo:

```text
Início

Leia nome
Leia idade

Fim
```

---

## 📤 Saída

Utilizamos `Escreva` para representar uma saída.

```text
Escreva nome
Escreva idade
```

Também podemos escrever uma mensagem:

```text
Escreva "Cadastro realizado"
```

---

## 📦 Atribuição

Utilizamos `←` para indicar que um valor será armazenado em uma variável.

```text
idade ← 28
nome ← "Jefferson"
```

Também podemos armazenar o resultado de uma operação:

```text
media ← (nota1 + nota2) / 2
```

---

## ➕ Operadores

### Aritméticos

```text
+   soma
-   subtração
*   multiplicação
/   divisão
```

Exemplo:

```text
total ← preco * quantidade
```

---

## 🔀 Decisão

Utilizamos `Se` para representar uma decisão.

### Se

```text
Se idade >= 18 Então
    Escreva "Maior de idade"
FimSe
```

### Se / Senão

```text
Se idade >= 18 Então
    Escreva "Maior de idade"
Senão
    Escreva "Menor de idade"
FimSe
```

### Condições encadeadas

```text
Se nota >= 7 Então
    Escreva "Aprovado"
Senão Se nota >= 5 Então
    Escreva "Recuperação"
Senão
    Escreva "Reprovado"
FimSe
```

---

## 🔁 Repetição

### Para

Utilizamos `Para` quando sabemos a quantidade ou intervalo de repetições.

```text
Para i de 1 até 5
    Escreva i
FimPara
```

### Enquanto

Utilizamos `Enquanto` quando a repetição depende de uma condição.

```text
Enquanto contador < 5
    Escreva contador
    contador ← contador + 1
FimEnquanto
```

### Faça-Enquanto

Utilizamos `Faça-Enquanto` quando o bloco precisa ser executado pelo menos uma vez.

```text
Faça
    Leia numero
Enquanto numero < 0
```

---

## 🧩 Exemplo completo

Problema:

> Receber duas notas, calcular a média e informar se o aluno foi aprovado.

```text
Início

Leia nota1
Leia nota2

media ← (nota1 + nota2) / 2

Se media >= 7 Então
    Escreva "Aprovado"
Senão
    Escreva "Reprovado"
FimSe

Fim
```

Observe a sequência:

```text
Entrada
   ↓
Processamento
   ↓
Decisão
   ↓
Saída
```

---

## 📌 Referência rápida

| Conceito | Pseudocódigo |
|---|---|
| Início | `Início` |
| Fim | `Fim` |
| Entrada | `Leia` |
| Saída | `Escreva` |
| Atribuição | `←` |
| Decisão | `Se ... Então` |
| Alternativa | `Senão` |
| Repetição | `Para` |
| Repetição condicional | `Enquanto` |
| Repetição pós-condicional | `Faça ... Enquanto` |

---

## 🔒 Regra do Playground

O pseudocódigo **não precisa seguir a sintaxe de Java**.

Seu objetivo é representar a lógica de maneira:

- clara;
- estruturada;
- sequencial;
- independente da linguagem.

> **Pseudocódigo é uma ferramenta para pensar e comunicar algoritmos, não uma linguagem que precisa ser decorada.**