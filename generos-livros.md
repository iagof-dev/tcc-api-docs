---
description: /generos_livros/
---

# 😆 Generos Livros

## GET

/listar/\[ID<mark style="color:red;">\*</mark>] - listar generos de um livro especifico por id

Resultado:

```
{
  "status": "success",
  "DATA": [
    {
      "id_livro": 1,
      "id_genero": 1,
      "titulo": "Aprendendo SQL",
      "genero": "Educação"
    },
    {
      "id_livro": 1,
      "id_genero": 2,
      "titulo": "Aprendendo SQL",
      "genero": "Tecnologia"
    }
  ]
}
```

## POST

/inserir/ - Inserir generos livros \[id\_genero<mark style="color:red;">\*</mark>, id\_livro<mark style="color:red;">\*</mark>]

/remover/ - Remover generos livros \[id\_genero<mark style="color:red;">\*</mark>, id\_livro<mark style="color:red;">\*</mark>]
