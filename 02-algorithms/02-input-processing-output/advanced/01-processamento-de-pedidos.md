## 🧩 Exercício 01 — Processamento de pedidos

### 🎯 Problema

Uma plataforma de comércio eletrônico precisa processar um pedido desde sua criação até a conclusão.

O pedido contém:

-   dados do cliente;
-   produtos;
-   quantidades;
-   valores;
-   endereço de entrega;
-   forma de pagamento.

O processamento envolve:

-   validação dos dados;
-   cálculo do valor dos produtos;
-   aplicação de descontos;
-   cálculo do frete;
-   análise do pagamento;
-   verificação do estoque;
-   definição do resultado do pedido.

### 🧠 Sua tarefa

Identifique:

1.  **Entradas**
2.  **Processamentos**
3.  **Saídas**
4.  **Relações entre os dados**
5.  **Dependências entre os processamentos**
6.  **Dados utilizados em cada processamento**
7.  **Resultados intermediários**
8.  **Resultado final**

Use:

```
Entradas:
...

Processamentos:
...

Saídas:
...

Relação entre dados:
...

Dependências:
...

Resultados intermediários:
...

Resultado final:
...
```

### 🔒 Restrições

-   ❌ Não escrever código.
-   ❌ Não pensar em Java.
-   ❌ Não criar pseudocódigo.
-   ❌ Não criar fluxograma.
-   ❌ Não definir arquitetura.
-   ❌ Não inventar regras de negócio.
-   ❌ Não definir fórmulas que não foram apresentadas.
-   ❌ Não resolver o algoritmo.

### 🎯 Desafio

Neste nível, o objetivo é perceber que **um processamento pode depender do resultado de outro processamento**:

```
Entradas
   ↓
Processamento A
   ↓
Resultado intermediário
   ↓
Processamento B
   ↓
Resultado intermediário
   ↓
Processamento C
   ↓
Resultado final
```

Você deve identificar **o fluxo dos dados**, sem ainda definir como implementá-lo.