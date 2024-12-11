---
title: Alteração ou cancelamento de um Boleto Híbrido
excerpt: ''
api:
  file: boleto-híbrido.json
  operationId: patch_v2-order-due-date-order-id
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço possibilita alterar dados e realizar a baixa (cancelamento) de um Boleto Híbrido já registrado.**

**Alteração de Boleto:**

- Para realizar alterações em um Boleto já registrado, é necessário o envio de informações que deseja alterar (data de vencimento, juros, multa, buyer, etc.).

**Cancelamento de Boleto:**

- Para cancelar um boleto já registrado, ele precisa estar com o status "pendente". Sendo assim necessário apenas o envio do campo "status" com o valor "cancelled" no corpo da requisição (Request Body).

**IMPORTANTE**

- Cada banco parceiro possui particularidades para alterações, para detalhamento e comparação acessar a planilha: **[Particularidades de cada banco](https://docs.google.com/spreadsheets/d/1BlwoRwfXhR8hLgUbrPTqDdXbBPVMi7L42bSzMJcYWhk/edit?usp=sharing) **