## 🧩 Exercício 02 — Plataforma financeira integrada

### 🎯 Problema

Uma plataforma financeira integra diferentes serviços:

```
Conta
Cartão
Transferência
Pagamento
Empréstimo
Investimento
```

Esses serviços compartilham informações, mas cada área precisa enxergar apenas o nível de detalhe necessário para realizar sua responsabilidade.

A plataforma possui os seguintes contextos:

```
Cliente
Operação financeira
Análise de risco
Atendimento
Auditoria
```

### 🧠 Sua tarefa

Faça uma análise de **múltiplos níveis de abstração**.

Identifique:

1.  Quais informações são essenciais para representar a **plataforma financeira** em alto nível.
2.  Quais informações são necessárias para representar cada serviço.
3.  Quais informações são relevantes para cada contexto.
4.  Quais informações podem ser ocultadas em cada nível.
5.  Quais informações aparecem em mais de um contexto, mas com níveis diferentes de detalhe.
6.  Quais informações são específicas de um único contexto.
7.  O que muda quando você passa de uma visão geral para uma visão específica.

Organize sua análise:

```
Plataforma financeira
│
├── Visão geral
│   ├── ...
│   └── ...
│
├── Serviços
│   ├── Conta
│   ├── Cartão
│   ├── Transferência
│   ├── Pagamento
│   ├── Empréstimo
│   └── Investimento
│
└── Contextos
    ├── Cliente
    ├── Operação financeira
    ├── Análise de risco
    ├── Atendimento
    └── Auditoria
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não definir implementação.
-   ❌ Não inventar regras financeiras.
-   ❌ Não assumir que uma informação precisa aparecer em todos os contextos.
-   ❌ Não tratar todos os níveis de detalhe como equivalentes.

### 🎯 Desafio final

Este é o **último exercício de Abstração**.

Aqui você precisa decidir **o que deve ser mostrado, o que deve ser ocultado e em qual nível de detalhe cada informação deve aparecer**, considerando o objetivo de cada contexto.