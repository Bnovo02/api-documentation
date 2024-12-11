---
title: Criar uma Cobrança com Boleto Híbrido
excerpt: ''
api:
  file: boleto-híbrido.json
  operationId: post_v2-order-due-date
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço registra um boleto híbrido (Boleto + QR Code Pix). **

**Caso o QR Code seja pago, o boleto é automaticamente cancelado e vice-versa para o caso de pagamento via código de barras.**

**Atualmente, este serviço está disponível na Shipay com os seguintes bancos parceiros:**

- Itaú
- Banco do Brasil
- Sicoob
- Bradesco
- Santander
- Sicredi

**IMPORTANTE:** 

- Cada banco parceiro possui particularidades para criação, alteração e cancelamento. Para detalhamento e comparação acessar a planilha: **[Particularidades de cada banco](https://docs.google.com/spreadsheets/d/1BlwoRwfXhR8hLgUbrPTqDdXbBPVMi7L42bSzMJcYWhk/edit?usp=sharing) **