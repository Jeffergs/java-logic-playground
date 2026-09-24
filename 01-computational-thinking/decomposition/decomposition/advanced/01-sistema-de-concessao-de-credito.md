## 🧩 Exercício 01 — Sistema de concessão de crédito

### 🎯 Problema

Uma instituição financeira precisa de um sistema para **analisar solicitações de crédito** e decidir se uma solicitação pode seguir para contratação.

O processo deverá:

-   receber os dados do cliente;
-   receber os dados da solicitação de crédito;
-   validar os dados informados;
-   verificar o histórico financeiro do cliente;
-   analisar a capacidade de pagamento;
-   aplicar as regras de concessão de crédito;
-   determinar o resultado da análise;
-   registrar a decisão;
-   informar o resultado ao cliente.

### 🔒 Restrições

Neste exercício:

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não pensar em banco de dados.
-   ❌ Não criar classes ou métodos.
-   ❌ Não implementar as regras de crédito.
-   ❌ Não assumir como as análises internas funcionam.

### 🧠 Sua tarefa

Faça uma **decomposição hierárquica** do problema.

Identifique:

1.  **Macroprocessos** do sistema.
2.  **Subprocessos** de cada macroprocesso.
3.  Quais subprocessos ainda precisam ser decompostos.
4.  **Dependências** entre as etapas.
5.  Onde existem diferentes responsabilidades dentro do processo.

Tente chegar a uma estrutura semelhante a:

```
Sistema de concessão de crédito
│
├── Processo A
│   ├── Subprocesso
│   └── Subprocesso
│
├── Processo B
│   ├── Subprocesso
│   └── Subprocesso
│
└── Processo C
    ├── Subprocesso
    └── Subprocesso
```

**Aqui o desafio não é encontrar muitas partes. É encontrar as partes certas e organizá-las em níveis de decomposição coerentes.**