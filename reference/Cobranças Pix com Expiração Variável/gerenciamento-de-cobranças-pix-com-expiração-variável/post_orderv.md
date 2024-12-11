---
title: Criar uma Cobrança Pix com Expiração Variável
excerpt: ''
api:
  file: cobranças-pix-com-expiração-variável.json
  operationId: post_orderv
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço cria cobranças Pix com expiração variável**

[Verificar bancos parceiros disponíveis](https://shipay.freshdesk.com/support/solutions/articles/154000127015-shipay-quais-s%C3%A3o-os-psps-em-produc%C3%A3o-)

**Recomendado para gerar cobranças com o tempo de expiração superior a 60 minutos.**

**IMPORTANTE:** 

- **Após a expiração da cobrança, não será possível realizar o pagamento da mesma.**
- **Caso seja necessário criar cobranças com tempo de expiração menor, é necessário utilizar o serviço de [criação de pagamentos imediatos](https://shipay-documentation.readme.io/reference/post_order) **