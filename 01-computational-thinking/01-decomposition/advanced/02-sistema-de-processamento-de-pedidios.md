## 🧩 Exercício 02 — Sistema de processamento de pedidos

### 🎯 Problema

Uma empresa de comércio eletrônico precisa de um sistema para **processar pedidos realizados por clientes**, desde a criação até a conclusão da entrega.

O processo deverá:

-   receber os dados do cliente;
-   receber os produtos do pedido;
-   validar os dados do pedido;
-   verificar a disponibilidade dos produtos;
-   calcular os valores do pedido;
-   processar o pagamento;
-   confirmar o pedido;
-   preparar os produtos para envio;
-   acompanhar a entrega;
-   atualizar o status do pedido;
-   informar o cliente sobre o andamento.

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não pensar em banco de dados.
-   ❌ Não criar classes ou métodos.
-   ❌ Não implementar as regras.
-   ❌ Não assumir detalhes que não foram fornecidos.

### 🧠 Sua tarefa

Faça uma **decomposição hierárquica** do processo.

Identifique:

1.  Os **macroprocessos**.
2.  Os **subprocessos** de cada macroprocesso.
3.  Os subprocessos que ainda precisam ser divididos.
4.  As **dependências** entre as etapas.
5.  As diferentes **responsabilidades** existentes no processo.

O objetivo é chegar a uma estrutura em que um processo complexo possa ser compreendido através de partes menores e organizadas.

```
Processamento de pedidos
│
├── Macroprocesso
│   ├── Subprocesso
│   │   ├── Subprocesso menor
│   │   └── Subprocesso menor
│   └── Subprocesso
│
├── Macroprocesso
│   └── Subprocesso
│
└── Macroprocesso
    ├── Subprocesso
    └── Subprocesso
```

**Faça a decomposição sem tentar solucionar os processos.**