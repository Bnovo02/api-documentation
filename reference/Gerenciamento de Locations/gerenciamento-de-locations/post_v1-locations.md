---
title: Criar uma nova location
excerpt: ''
api:
  file: gerenciamento-de-locations.json
  operationId: post_v1-locations
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
**Este serviço cria uma location no banco e registra na Shipay. **

**Recomendado para clientes que desejam utilizar um mesmo QrCode para realizar cobranças de diferentes valores, deve ser vinculado ao serviço de [cobranças para pagamentos com expiração variável](https://shipay-documentation.readme.io/reference/post_pdvauth-6).**

**Atualmente, este serviço está disponível na Shipay com o seguinte banco parceiro:**

- Itaú