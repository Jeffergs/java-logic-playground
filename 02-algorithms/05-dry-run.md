# 🧩 Dry Run - Apenas o conceito

## 🎯 Objetivo

Saber **simular mentalmente a execução de um algoritmo antes de executá-lo em uma linguagem de programação**.

O Dry Run permite verificar:

-   Se a sequência de passos está correta.
-   Como os valores das variáveis mudam.
-   Qual caminho o algoritmo percorre.
-   Qual será a saída produzida.
-   Onde pode existir um erro lógico.

* * *

## 🧠 Conceito

Dry Run significa executar um algoritmo **manualmente**, acompanhando cada instrução e registrando o estado das variáveis.

```
Algoritmo
   ↓
Execução passo a passo
   ↓
Acompanhamento das variáveis
   ↓
Verificação das decisões
   ↓
Resultado esperado
```

A ideia é executar o algoritmo como se você fosse o computador.



## 🔍 Processo

Para cada exercício:

```
1. Ler o algoritmo
        ↓
2. Identificar as variáveis
        ↓
3. Registrar os valores iniciais
        ↓
4. Executar uma instrução por vez
        ↓
5. Atualizar os valores
        ↓
6. Registrar decisões e caminhos
        ↓
7. Determinar a saída
```

Não pule diretamente para o resultado.

O objetivo é acompanhar **cada etapa da execução**.

* * *

## 📋 Tabela de acompanhamento

Uma forma comum de realizar o Dry Run é utilizar uma tabela:

| Passo | Instrução     | Variável A | Variável B | Saída |
| ----- | ------------- | ---------- | ---------- | ----- |
| 1     | Início        | —          | —          | —     |
| 2     | Atribuição    | 10         | —          | —     |
| 3     | Atribuição    | 10         | 5          | —     |
| 4     | Processamento | 15         | 5          | —     |
| 5     | Saída         | 15         | 5          | 15    |

A tabela deve representar o **estado das variáveis após cada etapa relevante**.

* * *

## 🔀 Dry Run com decisões

Quando existir uma decisão, registre:

1.  A condição avaliada.
2.  O resultado da condição.
3.  O caminho escolhido.

Exemplo:

```
Se idade >= 18 Então
```

Durante o Dry Run:

```
idade = 20

20 >= 18
     ↓
   VERDADEIRO
     ↓
Executa o caminho "Então"
```

Não execute o caminho que não foi escolhido.

* * *

## 🔁 Dry Run com repetições

Quando existir uma repetição, acompanhe cada execução do ciclo.

Exemplo conceitual:

```
contador ← 1

Enquanto contador <= 3
    ...
    contador ← contador + 1
FimEnquanto
```

O acompanhamento deve mostrar:

```
Iteração 1 → contador = 1
Iteração 2 → contador = 2
Iteração 3 → contador = 3
Fim → contador = 4
```

O objetivo é verificar **quantas vezes o ciclo é executado e como as variáveis são alteradas**.


## 💡 Princípio

> **Antes de executar um algoritmo em uma linguagem de programação, seja capaz de acompanhar manualmente cada passo da sua execução.**