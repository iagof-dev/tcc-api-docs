---
description: /emprestimos/
---

# 🎫 Emprestimos

## GET

/listar/ - Listar todos

/listar/rm/<mark style="color:yellow;">\[RM]</mark> - Listar todos livros emprestados por aluno

/listar/livro/<mark style="color:yellow;">\[ID]</mark> - Listar todos emprestimos por <mark style="color:yellow;">id do livro</mark>

/listar/pendentes - Listar livros pendentes que foram emprestado, mas ainda não está no prazo de devolução.

/listar/atrasados - Listar livros que passaram do prazo de devolução e não teve prazo estendido

/listar/restituidos - Listar livros que já foram devolvidos

/listar/perdidos - Listar livros perdidos

Resultado:

```
{
  "status": "success",
  "DATA": [
    {
      "id": 1,
      "rm": 221002,
      "nome": "Maria Santos",
      "titulo": "Aprendendo SQL",
      "autor": "Carlos Drummond",
      "data_aluguel": "2023-04-01",
      "data_devolucao": "2023-04-15",
      "estado": "pendente"
    },
    {
      "id": 2,
      "rm": 221003,
      "nome": "Carlos Pereira",
      "titulo": "Dados Avançados",
      "autor": "Clarice Lispector",
      "data_aluguel": "2023-04-05",
      "data_devolucao": "2023-04-19",
      "estado": "atrasado"
    }
  ]
}
```

## POST

/criar/ - Criar um emprestimo \[NOT FINISHED]

/modificar/ - Modificar estado do emprestimo \[ID<mark style="color:red;">\*</mark>,ID\_ESTADO<mark style="color:red;">\*</mark>]
