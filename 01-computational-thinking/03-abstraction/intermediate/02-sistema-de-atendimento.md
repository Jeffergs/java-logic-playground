## 🧩 Exercício 02 — Sistema de atendimento

### 🎯 Problema

Uma empresa possui um sistema de atendimento utilizado por diferentes áreas:

```
Atendimento ao cliente
Atendimento técnico
Atendimento financeiro
Atendimento administrativo
```

Todas as áreas utilizam o mesmo sistema, mas cada uma precisa visualizar e trabalhar com informações diferentes.

### 🧠 Sua tarefa

Determine:

1.  Quais informações são essenciais para representar um **atendimento** de forma geral.
2.  Quais informações são relevantes para cada área.
3.  Quais informações podem ser ocultadas dependendo da área.
4.  Quais informações precisam permanecer disponíveis em todas as áreas.
5.  Quais detalhes pertencem ao processo específico de cada tipo de atendimento.
6.  Qual seria o **nível adequado de abstração** para representar um atendimento de maneira geral.

Organize sua análise:

```
Atendimento
│
├── Visão geral
│   ├── ...
│   └── ...
│
├── Cliente
│   ├── ...
│   └── ...
│
├── Técnico
│   ├── ...
│   └── ...
│
├── Financeiro
│   ├── ...
│   └── ...
│
└── Administrativo
    ├── ...
    └── ...
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não definir implementação.
-   ❌ Não assumir informações técnicas não apresentadas.
-   ❌ Não considerar todas as informações como igualmente relevantes.

### 🎯 Objetivo

Neste exercício, você precisa perceber que **a mesma realidade pode ser representada de maneiras diferentes dependendo de quem precisa utilizá-la e para qual finalidade**.

> **A abstração adequada depende do contexto e do objetivo.**