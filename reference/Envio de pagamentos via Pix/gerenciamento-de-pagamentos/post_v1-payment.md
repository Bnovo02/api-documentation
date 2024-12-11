---
title: Solicitação de Criação de Pagamento
excerpt: ''
api:
  file: envio-de-pagamentos-via-pix.json
  operationId: post_v1-payment
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço cria uma solicitação de pagamento que debita o valor da conta bancária associada na Shipay e credita  via Pix na conta bancária informada.**

**É possível utilizar os seguintes dados para realizar transferências:**

- Chave Pix;
- Dados bancários.

**Atualmente, este serviço está disponível na Shipay com os seguintes bancos parceiros:**

- Tivit (Tbanks)
- Bs2
- Itaú
- Santander

**IMPORTANTE:** 

- No momento a criação de solicitação de pagamentos Pix via dados bancários,** está disponível somente para o banco Itaú.**
- Para acessar esse serviço, além da** [autenticação](https://shipay.readme.io/reference/post_pdvauth-2)**, é necessário configurar o certificado MTLS.  
  Para mais informações, acessar o **[passo a passo para criação do certificado MTLS.](https://docs.shipay.com.br/setupcashout.html)**