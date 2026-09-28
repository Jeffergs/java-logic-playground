# 🧩 03 — Abstração

## 🧠 Conceito

**Abstração** consiste em identificar os elementos essenciais de um problema, ignorando detalhes que não são relevantes para o objetivo naquele momento.

A ideia é:

```
Problema completo
       ↓
Identificar o que é relevante
       ↓
Ignorar detalhes desnecessários
       ↓
Representação simplificada
```

### Exemplo

Imagine um sistema de pagamento.

O processo pode envolver:

-   dados do cliente;
-   dados do cartão;
-   banco emissor;
-   autorização;
-   antifraude;
-   rede de pagamento;
-   comunicação com outros sistemas;
-   registros internos.

Se o objetivo for apenas **representar o conceito de pagamento**, não precisamos considerar todos esses detalhes.

Podemos abstrair para:

```
Pagamento
   │
   ├── Pagador
   ├── Valor
   └── Forma de pagamento
```

A abstração **não significa apagar informações permanentemente**.

Significa determinar:

> **Quais informações são relevantes para o problema que estou tentando resolver?**

* * *

## 🎯 Objetivo do Playground

Desenvolver a capacidade de:

-   identificar informações essenciais;
-   eliminar detalhes irrelevantes;
-   representar problemas de forma simplificada;
-   definir o nível adequado de detalhe;
-   separar o que é essencial do que é implementação.

* * *

## 📚 Organização

```
03-abstraction/
│
├── README.md
│
├── 01-basic/
├── 02-intermediate/
└── 03-advanced/
```

### 🟢 Basic

Identificar informações essenciais e ignorar detalhes claramente irrelevantes.

### 🟡 Intermediate

Determinar quais informações são relevantes dependendo do **objetivo do problema**.

### 🔴 Advanced

Trabalhar com diferentes níveis de abstração e decidir **o que deve ser exposto ou ocultado** em problemas mais complexos.

* * *

## 🔒 Restrições

Durante este Playground:

-   ❌ Não escrever código.
-   ❌ Não pensar inicialmente em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não confundir abstração com decomposição.
-   ❌ Não remover informações sem considerar o objetivo.
-   ❌ Não detalhar a implementação.

