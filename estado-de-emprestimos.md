---
description: /estado_emprestimos/
---

# ✨ Estado de Emprestimos

## GET

/<mark style="color:yellow;">listar</mark> - Listar todos os estados que um empréstimo poderá ter.

Resultado:

```
{
  "status": "success",
  "DATA": [
    {
      "id": 1,
      "estado": "pendente"
    },
    {
      "id": 2,
      "estado": "atrasado"
    },
    {
      "id": 3,
      "estado": "restituido"
    }
  ]
}
```

## POST

