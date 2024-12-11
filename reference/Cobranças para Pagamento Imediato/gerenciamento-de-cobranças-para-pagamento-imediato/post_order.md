---
title: Criar uma cobrança para pagamentos imediatos
excerpt: ''
api:
  file: cobranças-para-pagamento-imediato.json
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
**Este serviço gera QR Codes de cobrança para pagamento imediato.**

**Suporta os seguintes tipos de cobranças:**

* Pix
* Carteiras Digitais
* Criptomoedas

[Verificar bancos parceiros disponíveis](https://shipay.freshdesk.com/support/solutions/articles/154000127015-shipay-quais-s%C3%A3o-os-psps-em-produc%C3%A3o-)

**Recomendado para:**

* Sistemas de frente de caixa
* Checkouts de e-commerce
* Devices mobile de frente de caixa
* Chatbot
* Aplicativos
* Maquininhas (POS e SmartPOS)

**IMPORTANTE**

**Se não houver pagamento**, as cobranças criadas por este serviço serão expiradas em 60 minutos.
