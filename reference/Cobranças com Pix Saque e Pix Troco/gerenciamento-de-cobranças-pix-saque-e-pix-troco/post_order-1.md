---
title: Criar uma Cobrança com Pix Saque e Pix Troco
excerpt: ''
api:
  file: cobranças-com-pix-saque-e-pix-troco.json
  operationId: post_order
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço utiliza a mesma integração para criação de  **[QR Codes de cobrança imediata](https://shipay.readme.io/reference/post_order) e pode ser utilizado como Pix Saque ou Pix Troco.\*\*

- Pix saque: O valor da cobrança é referente à entrega de dinheiro em espécie para o solicitante.  
- Pix troco: o valor da cobrança é composto por duas parcelas, sendo: 
  \-Compra de um ou mais itens ou serviços.
  \-Entrega de dinheiro em espécie para o solicitante.

Para que a utilização deste serviço ocorra é necessário enviar na requisição os seguintes parâmetros no campo item>type:

- Para definir uma cobrança **Pix saque** é necessário enviar **"withdraw".**
- Para definir uma cobrança **Pix troco** é necessário enviar **"change".**

**Atualmente, este serviço está disponível na Shipay com o seguinte banco parceiro:**

- Sicredi

**Recomendado para sistemas de frente de caixa**

**IMPORTANTE:**

- **Se não houver pagamento**, as cobranças criadas por este serviço serão expiradas em 60 minutos.