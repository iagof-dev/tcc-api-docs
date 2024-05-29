---
description: /avaliacoes/
---

# ⭐ Avaliacoes

## GET

/id/<mark style="color:purple;">\[ID]</mark> - Listar avaliações por ID do livro

/media/<mark style="color:purple;">\[ID]</mark> - Listar média de avaliações por ID do livro.

Resultado <mark style="color:yellow;">Listagem</mark>:

```
{
  "status": "success",
  "DATA": [
    {
      "id": 1,
      "nome": "João Silva",
      "avaliacao": 4.5
    },
    {
      "id": 2,
      "nome": "Maria Santos",
      "avaliacao": 5
    },
    {
      "id": 3,
      "nome": "Maria Santos",
      "avaliacao": 2
    }
  ]
}
```

Resultado <mark style="color:yellow;">média</mark>:

```
{
  "status": "success",
  "DATA": [
    {
      "avaliadores": 3,
      "nota": 3.83333333333333
    }
  ]
}
```

## POST

