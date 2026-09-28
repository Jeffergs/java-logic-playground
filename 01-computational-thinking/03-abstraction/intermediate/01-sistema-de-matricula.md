## 🧩 Exercício 01 — Sistema de matrícula

### 🎯 Problema

Uma instituição de ensino precisa representar o processo de **matrícula de alunos**.

O sistema possui diferentes objetivos de análise:

```
Visão do aluno
Visão da secretaria
Visão financeira
Visão acadêmica
```

Cada visão precisa de informações diferentes sobre uma mesma matrícula.

### 🧠 Sua tarefa

Analise o problema e determine:

1.  Quais informações são essenciais para representar uma matrícula de forma geral.
2.  Quais informações são relevantes apenas para a **visão do aluno**.
3.  Quais informações são relevantes para a **secretaria**.
4.  Quais informações são relevantes para a **visão financeira**.
5.  Quais informações são relevantes para a **visão acadêmica**.
6.  Quais informações podem ser ocultadas em cada visão.
7.  Como a representação da matrícula muda conforme o **objetivo da análise**.

Organize sua análise:

```
Matrícula
│
├── Visão geral
│   ├── ...
│   └── ...
│
├── Visão do aluno
│   ├── ...
│   └── ...
│
├── Visão da secretaria
│   ├── ...
│   └── ...
│
├── Visão financeira
│   ├── ...
│   └── ...
│
└── Visão acadêmica
    ├── ...
    └── ...
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não definir implementação.
-   ❌ Não tentar criar uma representação que contenha todas as informações possíveis.
-   ❌ Não considerar uma informação essencial apenas porque ela existe no processo.

### 🎯 Objetivo

No **Intermediate**, a abstração deixa de ser apenas "o que posso ignorar?".

Agora a pergunta principal passa a ser:

> **"O que é relevante depende de qual é o objetivo da análise?"**

Você precisa encontrar o **nível adequado de abstração para cada perspectiva**.