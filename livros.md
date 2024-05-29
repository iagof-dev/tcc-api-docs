---
description: /livros/
---

# 📘 Livros

## GET

/listar/ - Lista todos os livros

/listar/codigo/<mark style="color:purple;">\[CÓDIGO]</mark> - Listar livro por código

/listar/genero/<mark style="color:purple;">\[ID\_GENERO]</mark> - Listar livro por genero

\-/listar/titulo/<mark style="color:purple;">\[VALOR]</mark> - Listar livro por titulo (Autocompletar)

\-/listar/autor/<mark style="color:purple;">\[VALOR]</mark> - Listar livro por autor (Autocompletar)

Resultado:

```
{
  "status": "success",
  "DATA": [
    {
      "id": 1,
      "codigo": "L001",
      "titulo": "Aprendendo SQL",
      "capa": "https://google.com/imagem1.webp",
      "autor": "Carlos Drummond",
      "editora": "Editora Alpha",
      "genero": "Educação",
      "avaliacao": 3.83333333333333
    },
    {
      "id": 2,
      "codigo": "L002",
      "titulo": "Dados Avançados",
      "capa": "https://google.com/imagem2.webp",
      "autor": "Clarice Lispector",
      "editora": "Editora Beta",
      "genero": "Tecnologia",
      "avaliacao": 0
    }
  ]
}
```

## POST

/criar/ - Criar livro | \[ID, CODIGO<mark style="color:red;">\*</mark>, TITULO<mark style="color:red;">\*</mark>, ID\_AUTOR<mark style="color:red;">\*</mark>, ID\_EDITORA<mark style="color:red;">\*</mark>, CAPA<mark style="color:red;">\*</mark>, VOLUMES<mark style="color:red;">\*</mark>, SINOPSE<mark style="color:red;">\*</mark>]

/modificar/ - Modificar informações | \[ID<mark style="color:red;">\*</mark>]

/deletar/ - Deletar livro | \[ID<mark style="color:red;">\*</mark>]
