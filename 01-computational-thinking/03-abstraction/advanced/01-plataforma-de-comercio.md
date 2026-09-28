## 🧩 Exercício 01 — Plataforma de comércio eletrônico

### 🎯 Problema

Uma plataforma de comércio eletrônico possui diferentes áreas que trabalham com o mesmo pedido:

```
Cliente
Vendedor
Estoque
Pagamento
Logística
Suporte
```

Cada área precisa de uma visão diferente do pedido. Algumas informações são importantes para várias áreas, enquanto outras são relevantes apenas para uma delas.

### 🧠 Sua tarefa

Analise o pedido e determine:

1.  Quais informações são **essenciais para representar um pedido**.
2.  Quais informações são relevantes para cada área.
3.  Quais informações podem ser ocultadas em cada contexto.
4.  Quais informações permanecem importantes independentemente da área.
5.  Quais informações são específicas de determinado processo.
6.  Quais níveis de abstração podem ser utilizados para representar o mesmo pedido.
7.  Onde uma informação deixa de ser relevante quando mudamos o contexto.

Organize sua análise:

```
Pedido
│
├── Visão geral
│   ├── ...
│   └── ...
│
├── Cliente
│   ├── ...
│   └── ...
│
├── Vendedor
│   ├── ...
│   └── ...
│
├── Estoque
│   ├── ...
│   └── ...
│
├── Pagamento
│   ├── ...
│   └── ...
│
├── Logística
│   ├── ...
│   └── ...
│
└── Suporte
    ├── ...
    └── ...
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não definir implementação.
-   ❌ Não inventar regras do negócio.
-   ❌ Não considerar todas as informações igualmente relevantes.
-   ❌ Não criar uma única representação que contenha tudo.

### 🎯 Desafio

No nível **Advanced**, o objetivo é trabalhar com **múltiplos níveis de abstração simultaneamente**.

Você deverá identificar não apenas _o que é essencial_, mas **qual informação é essencial para cada contexto e em qual nível de detalhe ela precisa ser representada**.

> **A abstração adequada não depende apenas da informação; depende do contexto, do objetivo e do nível de detalhe necessário.**