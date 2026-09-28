## 🧩 Exercício 03 — Sistema bancário

### 🎯 Problema

Um banco possui diferentes operações:

```
Conta corrente
Conta poupança
Conta de investimento
Cartão
Empréstimo
```

Todas fazem parte do contexto financeiro de um cliente, mas cada operação possui informações específicas.

O objetivo é criar uma representação para diferentes contextos:

```
Visão do cliente
Visão do gerente
Visão de análise financeira
Visão de auditoria
```

### 🧠 Sua tarefa

Analise o problema e determine:

1.  Quais informações são essenciais para representar a **situação financeira de um cliente**.
2.  Quais informações são relevantes para cada contexto.
3.  Quais informações podem ser ocultadas em cada contexto.
4.  Quais informações permanecem importantes independentemente da visão.
5.  Quais detalhes pertencem exclusivamente a cada operação.
6.  Em quais pontos a representação precisa ser mais ou menos detalhada.
7.  Onde uma informação pode ser relevante em um contexto, mas irrelevante em outro.

Organize sua análise:

```
Contexto financeiro do cliente
│
├── Visão geral
│   ├── ...
│   └── ...
│
├── Cliente
│   ├── ...
│   └── ...
│
├── Gerente
│   ├── ...
│   └── ...
│
├── Análise financeira
│   ├── ...
│   └── ...
│
└── Auditoria
    ├── ...
    └── ...
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não definir implementação.
-   ❌ Não inventar regras bancárias.
-   ❌ Não assumir que todas as visões precisam das mesmas informações.
-   ❌ Não tentar representar todos os detalhes em todas as visões.

### 🎯 Objetivo

Este é o **último exercício do nível Intermediate**.

O desafio é perceber que uma mesma realidade pode possuir **diferentes representações válidas**, dependendo do contexto e do nível de detalhe necessário.