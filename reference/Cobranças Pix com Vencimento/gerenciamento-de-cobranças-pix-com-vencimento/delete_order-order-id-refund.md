---
title: Realizar Devolução do pagamento de uma Cobrança
excerpt: ''
api:
  file: cobranças-pix-com-vencimento.json
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

**Trabalhamos hoje com dois tipos de estorno:**

**1) Estorno total:**Devolve o total do valor pago.

**2) Estorno parcial:** Devolve parcialmente o valor do pagamento efetuado, conforme informado na requisição.
