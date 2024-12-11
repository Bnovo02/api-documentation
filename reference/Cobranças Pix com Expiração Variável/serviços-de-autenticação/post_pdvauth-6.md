---
title: Autenticação para acesso aos serviços transacionais
excerpt: ''
api:
  file: cobranças-pix-com-expiração-variável.json
  operationId: post_pdvauth
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço gera um token de acesso para utilizar às APIs transacionais da Shipay.**

**Para gerar o token de acesso, é necessário o envio das seguintes credenciais na requisição:**

- access_key
- secret_key
- client_id

**Saiba como obter suas credenciais para API: [Criação de Credenciais](https://docs.shipay.com.br/cadastro.html)**

**IMPORTANTE:**  
O prazo de validade do token de acesso é informado na resposta desta API e **o mesmo token deve ser utilizado para quaisquer operações transacionais enquanto estiver válido.**