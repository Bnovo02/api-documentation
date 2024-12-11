---
title: Autenticação por sistema para acesso aos serviços
excerpt: ''
api:
  file: conciliação.json
  operationId: post_pdvsysauth
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço gera um token de acesso á nível de sistema para utilizar às APIs de cadastro e conciliação na Shipay.**

**Para gerar este token de acesso, é necessário o envio das seguintes credenciais na requisição:**

* access\_key
* pos\_product\_id

**Para obter essas credenciais, favor solicitar para nossa equipe de integração ([integracao@shipay.com.br]()).**

**IMPORTANTE:**

* O prazo de validade do token de acesso é informado na resposta desta API e **o mesmo token deve ser utilizado nas requisições enquanto estiver válido.**
