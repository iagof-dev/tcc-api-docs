---
description: /autores/
---

# ✍️ Autores

## GET

/listar/ - listar todos autores cadastros.

Resultado:

```
{
    "status": "success",
    "DATA": [
        {
            "id": 1,
            "autor": "Carlos Drummond"
        },
        {
            "id": 2,
            "autor": "Clarice Lispector"
        }
    ]
}
```

## POST

/adicionar/ - adicionar autor \[NOME<mark style="color:red;">\*</mark>]
