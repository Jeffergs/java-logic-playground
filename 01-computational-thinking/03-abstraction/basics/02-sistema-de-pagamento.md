## 🧩 Exercício 02 — Sistema de pagamento

### 🎯 Problema

Uma empresa precisa representar diferentes formas de pagamento:

```
Cartão de crédito
Cartão de débito
PIX
Boleto
Carteira digital
```

Cada forma possui informações e características próprias. Porém, o objetivo inicial é representar apenas o **conceito essencial de um pagamento**, sem entrar nos detalhes específicos de cada meio.

### 🧠 Sua tarefa

Analise as formas de pagamento e determine:

1.  Quais informações são **essenciais para representar um pagamento**.
2.  Quais informações são específicas de cada meio.
3.  Quais informações podem ser ignoradas nesse nível de análise.
4.  O que todas as formas de pagamento têm em comum.
5.  O que precisa permanecer específico de cada forma.
6.  Qual seria uma representação **simplificada** do conceito de pagamento.

Organize sua análise:

```
Pagamento
│
├── Essencial
│   ├── ...
│   └── ...
│
├── Específico
│   ├── Cartão
│   ├── PIX
│   ├── Boleto
│   └── ...
│
└── Detalhes que podem ser ignorados
    ├── ...
    └── ...
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não definir implementação.
-   ❌ Não entrar em detalhes técnicos.
-   ❌ Não remover informações sem justificar sua relevância para o objetivo.

### 🎯 Objetivo

Este é o **último exercício básico** de abstração.

Aqui você começa a perceber uma característica fundamental da abstração:

> **Uma representação pode esconder detalhes sem deixar de representar corretamente aquilo que é essencial.**