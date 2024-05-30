---
description: /editoras/
---

# 🏨 Editoras

## GET

/listar/ - listar todas as editoras registradas

Resultado:

```
{
    "status": "success",
    "DATA": [
        {
            "id": 1,
            "editora": "Editora Alpha"
        },
        {
            "id": 2,
            "editora": "Editora Beta"
        },
        {
            "id": 3,
            "editora": "Editora Sigma"
        }
    ]
}
```

## POST

/adicionar/ - registrar editora \[editora<mark style="color:red;">\*</mark>]
