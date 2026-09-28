## 🧩 Exercício 02 — Sistemas de autenticação

### 🎯 Problema

Uma empresa possui diferentes formas de autenticação:

```
Login com e-mail e senha
Login com código enviado por SMS
Login com código enviado por e-mail
Login por biometria
```

Todos os mecanismos têm o objetivo de **autenticar um usuário**, mas cada um possui características e etapas específicas.

### 🧠 Sua tarefa

Compare os quatro mecanismos e identifique:

1.  O que existe em comum entre eles.
2.  Quais etapas se repetem, mesmo que sejam executadas de formas diferentes.
3.  Quais características são específicas de cada mecanismo.
4.  Quais diferenças realmente distinguem um mecanismo do outro.
5.  Quais padrões podem ser identificados em um nível mais abstrato.

Organize sua análise em:

```
Padrões
│
├── Elementos comuns
├── Etapas recorrentes
└── Comportamentos semelhantes

Diferenças
│
├── E-mail e senha
├── SMS
├── E-mail
└── Biometria
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar classes ou métodos.
-   ❌ Não propor uma implementação.
-   ❌ Não transformar o padrão encontrado em uma solução.
-   ❌ Não assumir detalhes técnicos que não foram apresentados.

### 🎯 Objetivo

Neste exercício, procure padrões **menos óbvios**.

O desafio não é apenas perceber que todos "fazem login", mas identificar **estruturas e comportamentos que continuam semelhantes mesmo quando a forma de autenticação muda**.