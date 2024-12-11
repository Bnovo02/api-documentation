---
title: Realizar devolução do pagamento de uma cobrança
excerpt: ''
api:
  file: cobranças-para-pagamento-imediato.json
  operationId: delete_order-order-id-refund
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço realiza o estorno do pagamento de uma determinada cobrança.**

**É possível relizar dois tipos de estorno:**

**1) Estorno total:** Devolve o total do valor pago.

**2) Estorno parcial:** Devolve parcialmente o valor do pagamento efetuado, conforme informado na requisição.
